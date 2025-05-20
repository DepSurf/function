# Function: <code>lockdep_assert_cpus_held</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086950)
Location: kernel/cpu.c:238
Inline: True
Direct callers:
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81086950-ffffffff8108695b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d700)
Location: kernel/cpu.c:313
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff8108d700-ffffffff8108d70b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81091290)
Location: kernel/cpu.c:310
Inline: True
Direct callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/padata.c:padata_alloc_possible
```
**Symbols:**

```
ffffffff81091290-ffffffff8109129b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098f30)
Location: kernel/cpu.c:314
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/padata.c:padata_alloc_possible
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff81098f30-ffffffff81098f3b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d4b0)
Location: kernel/cpu.c:315
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/padata.c:padata_alloc_possible
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff8109d4b0-ffffffff8109d4bb: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3a00)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
```
**Symbols:**

```
ffffffff810a3a00-ffffffff810a3a0b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aaad0)
Location: kernel/cpu.c:319
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff810aaad0-ffffffff810aaadb: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6360)
Location: kernel/cpu.c:319
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff810a6360-ffffffff810a636b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a72c0)
Location: kernel/cpu.c:324
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff810a72c0-ffffffff810a72cb: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8cb0)
Location: kernel/cpu.c:335
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - mm/slub.c:flush_all_cpus_locked
```
**Symbols:**

```
ffffffff810b8cb0-ffffffff810b8cbb: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cf5f0)
Location: kernel/cpu.c:336
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - mm/slub.c:flush_all_cpus_locked
```
**Symbols:**

```
ffffffff810cf5f0-ffffffff810cf5ff: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ed9d0)
Location: kernel/cpu.c:336
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - mm/slub.c:flush_all_cpus_locked
```
**Symbols:**

```
ffffffff810ed9d0-ffffffff810ed9df: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9a80)
Location: kernel/cpu.c:515
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - mm/slub.c:flush_all_cpus_locked
```
**Symbols:**

```
ffffffff810f9a80-ffffffff810f9a8f: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102e90)
Location: kernel/cpu.c:515
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_partition_disable
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/jump_label.c:static_key_slow_dec_cpuslocked
  - kernel/jump_label.c:static_key_slow_dec
  - kernel/jump_label.c:jump_label_update_timeout
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - mm/slub.c:flush_all_cpus_locked
```
**Symbols:**

```
ffffffff81102e90-ffffffff81102e9f: lockdep_assert_cpus_held (STB_GLOBAL)
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
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9308)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
**Symbols:**

```
ffff8000100f9308-ffff8000100f9320: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357618)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
c0357618-c0357630: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001400b0)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_rebuild
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_teardown
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
c0000000001400b0-c0000000001400bc: lockdep_assert_cpus_held (STB_GLOBAL)
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
In kernel/cpu.c (0)
Location: include/linux/cpu.h:129
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpu.h:129
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpu.h:129
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/cpu.h:129
Inline: True
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
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d320)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
```
**Symbols:**

```
ffffffff8109d320-ffffffff8109d32b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bd40)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
```
**Symbols:**

```
ffffffff8108bd40-ffffffff8108bd4b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d2d0)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
```
**Symbols:**

```
ffffffff8109d2d0-ffffffff8109d2db: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lockdep_assert_cpus_held();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5150)
Location: kernel/cpu.c:318
Inline: True
Direct callers:
  - kernel/workqueue.c:apply_workqueue_attrs
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
```
**Symbols:**

```
ffffffff810a5150-ffffffff810a515b: lockdep_assert_cpus_held (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
