# Function: <code>class_rcu_constructor</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114e2ab)
Location: include/linux/rcupdate.h:1062
Inline: True
Inline callers:
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:get_nohz_timer_target
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
