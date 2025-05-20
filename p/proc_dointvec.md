# Function: <code>proc_dointvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81088c60)
Location: kernel/sysctl.c:2190
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rr_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81088c60-ffffffff81088c9a: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108b699)
Location: kernel/sysctl.c:2317
Inline: True
Inline callers:
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
Direct callers:
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff8108b600-ffffffff8108b63a: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810905e9)
Location: kernel/sysctl.c:2302
Inline: True
Inline callers:
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
Direct callers:
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81090550-ffffffff8109058a: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108dd90)
Location: kernel/sysctl.c:2459
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff8108dd90-ffffffff8108ddb9: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81094710)
Location: kernel/sysctl.c:2449
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81094710-ffffffff81094739: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81097fe0)
Location: kernel/sysctl.c:2454
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81097fe0-ffffffff81098009: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a02f0)
Location: kernel/sysctl.c:2502
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810a02f0-ffffffff810a0319: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4a30)
Location: kernel/sysctl.c:2588
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810a4a30-ffffffff810a4a5f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ab010)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810ab010-ffffffff810ab03f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b34a0)
Location: kernel/sysctl.c:802
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810b34a0-ffffffff810b34cf: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aecd0)
Location: kernel/sysctl.c:801
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810aecd0-ffffffff810aecff: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810afcc0)
Location: kernel/sysctl.c:813
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810afcc0-ffffffff810afcef: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c0e20)
Location: kernel/sysctl.c:857
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810c0e20-ffffffff810c0e4f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d84e0)
Location: kernel/sysctl.c:737
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - net/core/sysctl_net_core.c:proc_do_dev_weight
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810d84e0-ffffffff810d851b: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f97b7)
Location: kernel/sysctl.c:744
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dobool
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - net/core/sysctl_net_core.c:proc_do_dev_weight
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810f93a0-ffffffff810f93db: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81105b57)
Location: kernel/sysctl.c:743
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dobool
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/kexec_core.c:kexec_limit_handler
  - kernel/kexec_core.c:kexec_limit_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - net/core/sysctl_net_core.c:proc_do_dev_weight
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81105740-ffffffff8110577b: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110f4a7)
Location: kernel/sysctl.c:743
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dobool
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/kexec_core.c:kexec_limit_handler
  - kernel/kexec_core.c:kexec_limit_handler
  - kernel/latencytop.c:sysctl_latencytop
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - security/apparmor/lsm.c:userns_restrict_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - net/core/sysctl_net_core.c:proc_do_dev_weight
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/sysctl_net_ipv4.c:proc_udp_hash_entries
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_ehash_entries
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff8110f090-ffffffff8110f0cb: proc_dointvec (STB_GLOBAL)
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
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010103590)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_proc_do_default_vl
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffff800010103590-ffff8000101035f8: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035f628)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
c035f628-c035f678: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014b3e0)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
c00000000014b3e0-c00000000014b420: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca328)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffe0000ca328-ffffffe0000ca378: proc_dointvec (STB_GLOBAL)
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
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4930)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810a4930-ffffffff810a495f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093310)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff81093310-ffffffff8109333f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a48e0)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810a48e0-ffffffff810a490f: proc_dointvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ac9a0)
Location: kernel/sysctl.c:2590
Inline: True
Direct callers:
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/latencytop.c:sysctl_latencytop
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/util.c:overcommit_ratio_handler
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/mq_sysctl.c:proc_mq_dointvec
  - security/apparmor/lsm.c:apparmor_dointvec
  - drivers/char/random.c:proc_do_entropy
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/neighbour.c:neigh_proc_dointvec
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/route.c:ipv6_sysctl_rtcache_flush
```
**Symbols:**

```
ffffffff810ac9a0-ffffffff810ac9cf: proc_dointvec (STB_GLOBAL)
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
