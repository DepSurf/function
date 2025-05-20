# Function: <code>static_key_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81f6910e)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In kernel/sched/core.c (ffffffff810a6ac7)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sysctl_numa_balancing
```
```
In kernel/cgroup.c (ffffffff8111270d)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:cgroup_subtree_control_write
```
```
In kernel/cpuset.c (ffffffff8111a83e)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/tracepoint.c (ffffffff8113f8a2)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/jump_label.c (ffffffff8118ac83)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
```
```
In mm/oom_kill.c (ffffffff81191103)
Location: include/linux/jump_label.h:120
Inline: True
```
```
In mm/page_alloc.c (ffffffff81196007)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811a2a33)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
```
In mm/hugetlb.c (ffffffff811dca48)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/slub.c (ffffffff811eaaf3)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In lib/once.c (ffffffff81400e47)
Location: include/linux/jump_label.h:120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81786d15)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv6/udp.c (ffffffff817e18c5)
Location: include/linux/jump_label.h:120
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_encap_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d992)
Location: kernel/jump_label.c:69
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
Direct callers:
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff8119d270-ffffffff8119d287: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811ad3b2)
Location: kernel/jump_label.c:69
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
Direct callers:
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811acc40-ffffffff811acc57: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b4852)
Location: kernel/jump_label.c:70
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:static_key_disable
  - kernel/jump_label.c:static_key_enable
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - net/ipv4/udp.c:udp_encap_enable
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811b4070-ffffffff811b4087: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8654)
Location: kernel/jump_label.c:70
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff811c7db0-ffffffff811c7dc7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8bc3)
Location: kernel/jump_label.c:71
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff811e82e0-ffffffff811e82f7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f98f9)
Location: kernel/jump_label.c:89
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff811f8f70-ffffffff811f8f87: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211832)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff81210df0-ffffffff81210e07: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121eba2)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff8121e640-ffffffff8121e657: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b0ee)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/bpf/syscall.c:bpf_enable_stats
  - mm/page_reporting.c:page_reporting_register
```
**Symbols:**

```
ffffffff8124a890-ffffffff8124a8a7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8125554e)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:bpf_enable_stats
  - mm/page_reporting.c:page_reporting_register
```
**Symbols:**

```
ffffffff81254c30-ffffffff81254c47: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259a4d)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__do_sys_bpf
  - mm/page_reporting.c:page_reporting_register
```
**Symbols:**

```
ffffffff812591e0-ffffffff812591f7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295713)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__sys_bpf
  - mm/page_reporting.c:page_reporting_register
  - lib/once.c:once_deferred
```
**Symbols:**

```
ffffffff81294ee0-ffffffff81294ef7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb50a)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/build_utility.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__sys_bpf
  - mm/page_reporting.c:page_reporting_register
  - lib/once.c:once_deferred
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
```
**Symbols:**

```
ffffffff812eaab0-ffffffff812eaacf: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813555ca)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/build_utility.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__sys_bpf
  - mm/page_reporting.c:page_reporting_register
  - lib/once.c:once_deferred
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
```
**Symbols:**

```
ffffffff81354a00-ffffffff81354a1f: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386bac)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/build_utility.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__sys_bpf
  - mm/page_reporting.c:page_reporting_register
  - lib/once.c:once_deferred
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
```
**Symbols:**

```
ffffffff81385d90-ffffffff81385daf: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813b0097)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/build_utility.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/syscall.c:__sys_bpf
  - mm/page_reporting.c:page_reporting_register
  - lib/once.c:once_deferred
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
```
**Symbols:**

```
ffffffff813af250-ffffffff813af26f: static_key_count (STB_GLOBAL)
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
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102aad38)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffff8000102aa790-ffff8000102aa7c0: static_key_count (STB_GLOBAL)
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
In init/main.c (c0303658)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/arm/kernel/ptrace.c (c030d0c0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm/kernel/smp.c (c0313978)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
```
```
In arch/arm/kernel/swp_emulate.c (c0315c98)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In arch/arm/mm/fault.c (c0e9f9c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
  - arch/arm/mm/fault.c:do_page_fault
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/common/bL_switcher.c (c03267f4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d650)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In arch/arm/mach-omap2/powerdomain.c (c03451c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
```
```
In kernel/fork.c (c0353470)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c0357e10)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (c03598c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (c035bf60)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sysctl.c (c035fbac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/signal.c (c0368a14)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (c0373e0c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (c037aa60)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (c037fea0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (c0382704)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/clock.c (c038ebdc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_cpu
```
```
In kernel/sched/idle.c (c038f824)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (c0393790)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e0d8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a3018)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9e80)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/pelt.c (c03ab44c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/debug.c (c03af53c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_cfs_group_stats
```
```
In kernel/sched/cpufreq_schedutil.c (c03b13ac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/sched/isolation.c (c03b2938)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In kernel/sched/psi.c (c03b3a10)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/sched/psi.c:psi_trigger_replace
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/power/qos.c (c03b8ec8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (c03ba9f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (c03bb658)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (c03bc9d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/printk/printk.c (c15208e0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (c03c9eac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (c03cfdb4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/rcu/tree.c (c03dd830)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/time/timer.c (c03e9fb8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (c03ec4e4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (c03f5074)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (c03f84c0)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In kernel/time/itimer.c (c03fabc8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (c03fc9b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (c03ff364)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/module.c (c040c764)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (c041a608)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (c041e86c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (c041f8f0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (c0425424)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/hung_task.c (c0445d74)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (c0447dd0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/tracepoint.c (c044d334)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/trace/trace.c (c04635dc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/trace/bpf_trace.c (c047f9c0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
```
```
In kernel/bpf/core.c (c04929cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In kernel/bpf/devmap.c (c04b6778)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (c04b798c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/cgroup.c (c04bd530)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (c04c0654)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In kernel/rseq.c (c04d9ab8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (c04df9b8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (c04e4454)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (c04e6fa4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (c04ed460)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (c04f4120)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (c04fba90)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/backing-dev.c (c05033b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (c05070ac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (c0509d44)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (c05110c0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/list_lru.c (c0512f64)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (c05136b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (c051bc88)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c052621c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (c05336e8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/shuffle.c (c15be4a4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_free_memory
```
```
In mm/page_io.c (c0539328)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_writepage
```
```
In mm/swapfile.c (c053e6cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/dmapool.c (c05430a0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (c05501bc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:setup_slub_debug
  - mm/slub.c:setup_slub_debug
```
```
In mm/migrate.c (c0552bb0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (c1534284)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_bind
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In mm/page_isolation.c (c055eeac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (c0562f3c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In mm/usercopy.c (c0565174)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/open.c (c0569a30)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (c0575d28)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/pipe.c (c05767e8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/namei.c (c0579d18)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (c058e2fc)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/fs-writeback.c (c05a5244)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (c05b1934)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/block_dev.c (c05ba7e0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/locks.c (c05e32b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (c0606074)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/proc_sysctl.c (c060f564)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/balloc.c (c0621624)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (c0624110)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (c062da28)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (c063175c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (c0633724)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (c0633da0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c06361c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c0639130)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (c0645b98)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064e118)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (c06553e0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (c0664564)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/ext4/super.c (c0675c18)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/jbd2/transaction.c (c068decc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
```
In fs/jbd2/commit.c (c0690ba0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (c0693b98)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c0699060)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (c0789248)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (c0790e80)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (c07969f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (c079d15c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-sched.c (c07a1c18)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (c07b3400)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (c07bb4f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (c07c3158)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In block/blk-wbt.c (c07c94ec)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/once.c (c07dd360)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In lib/crc-t10dif.c (c07e8308)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/irqchip/irq-gic.c (c154b0f0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c154c1ac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
```
In drivers/gpio/gpiolib.c (c08622c4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer.c (c089c978)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/clk/clk.c (c08e7fa8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
```
```
In drivers/dma/tegra20-apb-dma.c (c092a390)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_tasklet
```
```
In drivers/regulator/core.c (c094b10c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (c09aa594)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (c09bc394)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (c09d97f0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (c09e5508)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (c09e6708)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (c09ed060)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (c09ede10)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (c09f89a0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (c09fdf8c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (c0a3d360)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (c0a40f78)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (c0a48468)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c0a4cfb8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-core.c (c0a6a700)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (c0a79804)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (c0ab3390)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (c0abee64)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (c0ac65c0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2ce0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0addcb8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/usb/host/xhci.c (c0b49eb8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (c0b4ce60)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (c0b51174)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (c0b595cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e434)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (c0b632dc)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b678cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_interrupt
  - drivers/usb/musb/musb_core.c:musb_writel
  - drivers/usb/musb/musb_core.c:musb_readl
  - drivers/usb/musb/musb_core.c:musb_default_writew
  - drivers/usb/musb/musb_core.c:musb_default_readw
  - drivers/usb/musb/musb_core.c:musb_default_writeb
  - drivers/usb/musb/musb_core.c:musb_default_readb
```
```
In drivers/usb/musb/musb_trace.c (c0b690f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/musb/musb_trace.c:musb_dbg
```
```
In drivers/usb/musb/musb_host.c (c0b6b4dc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_urb_dequeue
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_giveback
  - drivers/usb/musb/musb_host.c:musb_start_urb
```
```
In drivers/usb/musb/musb_gadget.c (c0b6fdac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_dequeue
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_gadget.c:musb_ep_restart
  - drivers/usb/musb/musb_gadget.c:musb_free_request
  - drivers/usb/musb/musb_gadget.c:musb_alloc_request
  - drivers/usb/musb/musb_gadget.c:musb_g_rx
  - drivers/usb/musb/musb_gadget.c:musb_g_tx
  - drivers/usb/musb/musb_gadget.c:musb_g_giveback
```
```
In drivers/usb/gadget/udc/core.c (c0b73980)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_giveback_request
  - drivers/usb/gadget/udc/core.c:usb_gadget_activate
  - drivers/usb/gadget/udc/core.c:usb_gadget_deactivate
  - drivers/usb/gadget/udc/core.c:usb_gadget_disconnect
  - drivers/usb/gadget/udc/core.c:usb_gadget_connect
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_disconnect
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_draw
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_connect
  - drivers/usb/gadget/udc/core.c:usb_gadget_clear_selfpowered
  - drivers/usb/gadget/udc/core.c:usb_gadget_set_selfpowered
  - drivers/usb/gadget/udc/core.c:usb_gadget_wakeup
  - drivers/usb/gadget/udc/core.c:usb_gadget_frame_number
  - drivers/usb/gadget/udc/core.c:usb_ep_fifo_flush
  - drivers/usb/gadget/udc/core.c:usb_ep_fifo_status
  - drivers/usb/gadget/udc/core.c:usb_ep_set_wedge
  - drivers/usb/gadget/udc/core.c:usb_ep_clear_halt
  - drivers/usb/gadget/udc/core.c:usb_ep_set_halt
  - drivers/usb/gadget/udc/core.c:usb_ep_dequeue
  - drivers/usb/gadget/udc/core.c:usb_ep_queue
  - drivers/usb/gadget/udc/core.c:usb_ep_free_request
  - drivers/usb/gadget/udc/core.c:usb_ep_alloc_request
  - drivers/usb/gadget/udc/core.c:usb_ep_disable
  - drivers/usb/gadget/udc/core.c:usb_ep_enable
  - drivers/usb/gadget/udc/core.c:usb_ep_set_maxpacket_limit
```
```
In drivers/rtc/interface.c (c0b88e9c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (c0b921b8)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b95640)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/hwmon/hwmon.c (c0bb197c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (c0bb3928)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (c0bb8c54)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (c0bba0c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (c0bba848)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (c0bbbaa8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc26c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_power2state
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c0bbd15c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (c0bdea00)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (c0becdd0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (c0bee448)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (c0bfb594)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
```
In drivers/cpuidle/cpuidle.c (c0c01be4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (c0c07a94)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e530)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (c0c675f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/ras.c (c0c80458)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In sound/soc/soc-dapm.c (c0ca9c68)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_seq_check_event
  - sound/soc/soc-dapm.c:dapm_seq_check_event
  - sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets
  - sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level
  - sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level
```
```
In sound/soc/soc-jack.c (c0cad3a4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:gpio_handler
```
```
In net/socket.c (c0cc6de4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
```
```
In net/core/sock.c (c0cc8778)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__release_sock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd6320)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/datagram.c (c0cd8150)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/secure_seq.c (c0cdd8f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (c0ce010c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (c0cefc0c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/ethtool.c (c0cf34bc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/ethtool.c:netdev_rss_key_fill
```
```
In net/core/neighbour.c (c0cfe680)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (c0d1c798)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e1f4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (c0d1f858)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/page_pool.c (c0d252d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d267b4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (c0d28f1c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/ptp_classifier.c (c0d34c64)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In net/core/lwt_bpf.c (c0d36078)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In net/core/devlink.c (c0d3c4d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (c0d4a718)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (c0d627dc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/route.c (c0d6815c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_output.c (c0d716b4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/inet_hashtables.c (c0d78de8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_connection_sock.c (c0d7cad8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d84338)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c0d88758)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (c0d93d08)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_options_write
```
```
In net/ipv4/tcp_timer.c (c0d9833c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (c0d99c94)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c0d9e638)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/udp.c (c0da6dd0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv4/udp_offload.c (c0dad3d8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c0db90dc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_dgram_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/fib_trie.c (c0dc7ea4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/syncookies.c (c0ddb80c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/af_inet6.c (c0dfc234)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/ip6_output.c (c0e033f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (c0e177d8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (c0e287e4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c0e2e2ac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (c0e3b660)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e3ff28)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/udp_offload.c (c0e438cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/syncookies.c (c0e4d474)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/seg6_local.c (c0e523e8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (c0e559c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/packet/af_packet.c (c0e5c5f0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In lib/vsprintf.c (c0e92d68)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f380)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - lib/once.c:once_deferred
```
**Symbols:**

```
c00000000035e490-c00000000035e4b0: static_key_count (STB_GLOBAL)
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
In init/main.c (ffffffe0000b432a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/riscv/kernel/ptrace.c (ffffffe0000b64c8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9bec)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - arch/riscv/mm/fault.c:do_page_fault
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (ffffffe0000c1410)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffe0000c3068)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffe0000c54a4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffe0000c7152)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sysctl.c (ffffffe0000ca77e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/signal.c (ffffffe0000d0bce)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffe0000d8e6e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffe0000df364)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (ffffffe0000e3ade)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffe0000e5b62)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/clock.c (ffffffe0000ed4e4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_cpu
```
```
In kernel/sched/idle.c (ffffffe0000edd40)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (ffffffe0000f0804)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c1c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd27e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe000102518)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/pelt.c (ffffffe0001030ca)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/debug.c (ffffffe000106a9a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_cfs_group_stats
```
```
In kernel/sched/isolation.c (ffffffe0001087c0)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In kernel/sched/psi.c (ffffffe0001098ac)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_fop_poll
  - kernel/sched/psi.c:psi_trigger_replace
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/power/qos.c (ffffffe00010d516)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffe00010d7de)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/printk/printk.c (ffffffe000007e3e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffe000113142)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffe000117fec)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/rcu/tree.c (ffffffe000121e42)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/dma/swiotlb.c (ffffffe00012874e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/time/timer.c (ffffffe0008c86ae)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffe00012e582)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/alarmtimer.c (ffffffe000135332)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffe00013753e)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In kernel/time/itimer.c (ffffffe0001391d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-sched.c (ffffffe00013b71a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/module.c (ffffffe000145ea8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffe000150a02)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154590)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffe000155414)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a832)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/hung_task.c (ffffffe00016979e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (ffffffe00016b294)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/tracepoint.c (ffffffe00016f546)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
```
In kernel/trace/trace.c (ffffffe000180ed0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
```
In kernel/bpf/core.c (ffffffe00019d4a0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_init_once
```
```
In kernel/bpf/devmap.c (ffffffe0001bb340)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc4cc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/cgroup.c (ffffffe0001c16b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (ffffffe0001c3844)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In mm/filemap.c (ffffffe0001d8072)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffe0001dbb10)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffe0001de1ba)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffe0001e3672)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffe0001e93e8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffe0001ef86a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/backing-dev.c (ffffffe0001f608a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffe0001f9f92)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffe0001fb9e6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffe000201860)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/list_lru.c (ffffffe000203208)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffe000203800)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffe000209afc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffe0002139de)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffe00021ea84)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/shuffle.c (ffffffe00004781c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_free_memory
```
```
In mm/page_io.c (ffffffe000221f84)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_writepage
```
```
In mm/swapfile.c (ffffffe00022708c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/dmapool.c (ffffffe00022b914)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffffffe00022c082)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In mm/slub.c (ffffffe00023d6f4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:setup_slub_debug
  - mm/slub.c:setup_slub_debug
```
```
In mm/migrate.c (ffffffe00023fbe6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffe00001959c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_bind
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_memcg
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge_memcg
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a608)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/page_isolation.c (ffffffe00024b424)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffe00024f3a4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In mm/usercopy.c (ffffffe0002511e2)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/open.c (ffffffe000254d0e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffe00025ee20)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/pipe.c (ffffffe00025f7b2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/namei.c (ffffffe0002632f2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/inode.c (ffffffe0002729ce)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/fs-writeback.c (ffffffe00028704e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffe000291626)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/block_dev.c (ffffffe000298b84)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/dax.c (ffffffe0002b356c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffe0002bf30a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffe0002d72d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/proc_sysctl.c (ffffffe0002df85a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/balloc.c (ffffffe0002f0172)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffe0002f2304)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffe0002f9b74)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffe0002fca86)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffe0002fe2f8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffe0002fe800)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffe000300630)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffe00030293c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffe00030c9e4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffe0003129ba)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffe000318914)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffe000324092)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In fs/ext4/super.c (ffffffe000330472)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/jbd2/transaction.c (ffffffe00034378c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
```
In fs/jbd2/commit.c (ffffffe000345b80)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffe0003484bc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034cee6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (ffffffe00041f256)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffe0004255b6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffe00042a91a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffe00042fd44)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-sched.c (ffffffe000433e3a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/blk-throttle.c (ffffffe000448884)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffe00044e184)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/blk-wbt.c (ffffffe000453e36)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/once.c (ffffffe00046496a)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In lib/crc-t10dif.c (ffffffe00046ea3a)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a88bc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d36d0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/clk/clk.c (ffffffe00050b7ec)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/regulator/core.c (ffffffe0005236ae)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffe0005622b8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/base/power/qos.c (ffffffe000589272)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffe00058b1f0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/regmap/regmap.c (ffffffe000594444)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffe000598748)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3326)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d66ae)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc7b6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0996)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-core.c (ffffffe0005fae52)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffe000607978)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffe00061998a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffe0006233e2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffe00062af90)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d334)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/usb/host/xhci.c (ffffffe00068e2dc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000690ca4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000694aa2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069be66)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069fad0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a4434)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/rtc/interface.c (ffffffe0006b55fa)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8dca)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbac6)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cd848)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cf6d0)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffe0006d31c4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffe0006d44e0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffe0006d4ad2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d5756)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d6010)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (ffffffe0006eee02)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffe0006fbccc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffe0006fd3de)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/mmc/core/core.c (ffffffe00070684c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/devfreq/devfreq.c (ffffffe00072d912)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffe0007368be)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/socket.c (ffffffe00073bc00)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
```
```
In net/core/sock.c (ffffffe00073d60c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__release_sock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe000748edc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/datagram.c (ffffffe00074abd6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/secure_seq.c (ffffffe00074f52a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcp_ts_off
  - net/core/secure_seq.c:secure_ipv6_port_ephemeral
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/secure_seq.c:secure_tcpv6_ts_off
```
```
In net/core/flow_dissector.c (ffffffe0007515fc)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffe00075e2d2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/ethtool.c (ffffffe000762b48)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In net/core/neighbour.c (ffffffe00076ab30)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffe000782484)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffe000783988)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffffffe000784cb0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/page_pool.c (ffffffe000789d28)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffe00078ae88)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (ffffffe00078d0e4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/ptp_classifier.c (ffffffe000796afa)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe000797d96)
Location: include/linux/jump_label.h:252
Inline: True
```
```
In net/core/devlink.c (ffffffe00079d832)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffe0007aa17e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/bpf/test_run.c (ffffffe0007bd8b6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/route.c (ffffffe0007c24ce)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_output.c (ffffffe0007c9d8c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf966)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d35b0)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d8e4e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffffffe0007de516)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6414)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_options_write
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea22a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb2b8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef8f2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/udp.c (ffffffe0007f6e3c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_flow_hashrnd
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd4f6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe000806a1a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_dgram_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/fib_trie.c (ffffffe000812b08)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/syncookies.c (ffffffe000822e26)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
```
In net/ipv6/af_inet6.c (ffffffe0008411d8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/ip6_output.c (ffffffe0008469da)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffe000857b90)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffe000865c4c)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffe00086aaf8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087553a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe0008796e2)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/udp_offload.c (ffffffe00087c68e)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/syncookies.c (ffffffe000884fd8)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_hash
```
```
In net/ipv6/seg6_local.c (ffffffe000889a2a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cbd6)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/packet/af_packet.c (ffffffe00089387a)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In lib/vsprintf.c (ffffffe0008bf6d4)
Location: include/linux/jump_label.h:252
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812171f2)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff81216c90-ffffffff81216ca7: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81209f52)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff812099f0-ffffffff81209a07: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81214f92)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff81214a30-ffffffff81214a47: static_key_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int static_key_count(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81223f42)
Location: kernel/jump_label.c:104
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/clock.c:clear_sched_clock_stable
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff812239e0-ffffffff812239f7: static_key_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
