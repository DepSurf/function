# Function: <code>task_cputime</code>

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
In kernel/exit.c (ffffffff810824fb)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8108e93b)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810b16a1)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f24b8)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffff8110c28d)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2041
Inline: True
```
```
In kernel/tsacct.c (ffffffff8113f199)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81267445)
Location: include/linux/sched.h:2041
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269963)
Location: include/linux/sched.h:2041
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81085543)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810919bb)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810b4131)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810faa04)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff81113aed)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2183
Inline: True
```
```
In kernel/tsacct.c (ffffffff8114779f)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81294ee6)
Location: include/linux/sched.h:2183
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81295c63)
Location: include/linux/sched.h:2183
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108a4c5)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8109694b)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810ba771)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81108384)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff8111b1fd)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2268
Inline: True
```
```
In kernel/tsacct.c (ffffffff8115163f)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff812a9b8e)
Location: include/linux/sched.h:2268
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812aa8b3)
Location: include/linux/sched.h:2268
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81087551)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81093c62)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810b4ff1)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a600)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff8111ce1b)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (0)
Location: include/linux/sched/cputime.h:24
Inline: True
```
```
In kernel/taskstats.c (ffffffff81153446)
Location: include/linux/sched/cputime.h:24
Inline: True
```
```
In kernel/tsacct.c (ffffffff81153cd1)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff812b650b)
Location: include/linux/sched/cputime.h:24
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b95f1)
Location: include/linux/sched/cputime.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e2e1)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8109ab52)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810bc881)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811157b0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff8112852b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (0)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/taskstats.c (ffffffff8115fc46)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff811604d1)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff812d9dcb)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dcf00)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81091d9f)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/signal.c (ffffffff8109ea99)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810c3f31)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121e90)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff8113642e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff8116e1c5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff8116ebbc)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff8116f65b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff813042dd)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81307bee)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109a08f)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/signal.c (ffffffff810a6d97)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810cd1f1)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d5b0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff81141bbe)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff8117bc05)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff8117c6bc)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff8117d15b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81319a2d)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d3fe)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e6ac)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810ace43)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810d55e7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81137fc0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
```
```
In kernel/acct.c (ffffffff8114cfa4)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff81188a25)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff81189560)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118a01b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81342acc)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8134645c)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a4c39)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b3463)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810dfba7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114410e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffff81158c74)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff81194965)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff811954a0)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff81195f2b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff8135af02)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e764)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810abed7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810bbe8b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810e7ef5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153d0e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/acct.c (ffffffff81169884)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff811a99c5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff811aa3db)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811ab10b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff8139ea0e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2b80)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
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
In kernel/exit.c (ffffffff810a7577)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b7173)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810e5441)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115015d)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/acct.c (ffffffff81165fd6)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff811a6fe5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff811a797b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a86bb)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff813afff3)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3bf5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
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
In kernel/exit.c (ffffffff810a8607)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b8773)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810e73f1)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115158d)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/acct.c (ffffffff81166d00)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff811a7b25)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff811a835b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a923b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff813b7649)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813badb3)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
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
In kernel/exit.c (ffffffff810ba0e7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810cac63)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810fea01)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8117598d)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/acct.c (ffffffff8118c4c0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff811d1658)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff811d1c37)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811d2d8b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81407329)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8140aab3)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
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
In kernel/exit.c (ffffffff810d0bb0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810e40ed)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_policy.c (ffffffff8112f814)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa941)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/acct.c (ffffffff811bb8a6)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff81205c08)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff81206448)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81207749)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff8147beef)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f870)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
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
In kernel/exit.c (ffffffff810ef590)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8110476d)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_policy.c (ffffffff811598b4)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811eaa31)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/acct.c (ffffffff811fd70e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff8124ddd8)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff8124e748)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff8124fafc)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff8150e92f)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff815129c0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
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
In kernel/exit.c (ffffffff810fb534)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff811109ed)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/build_policy.c (ffffffff81169ac4)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff181)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/acct.c (ffffffff8121288e)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff81265138)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff81265af8)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81266eac)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff815460ee)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a400)
Location: include/linux/sched/cputime.h:16
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool task_cputime(struct task_struct *t, u64 *utime, u64 *stime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81182910)
Location: kernel/sched/cputime.c:850
Inline: True
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/sched/build_policy.c:task_cputime_adjusted
  - kernel/sched/build_policy.c:thread_group_cputime
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample
  - kernel/acct.c:acct_collect
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/delayacct.c:delayacct_add_tsk
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff81182910-ffffffff81182a09: task_cputime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100faa90)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffff80001010f2a0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffff80001013f670)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae6a0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffff8000101c8190)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffff80001020ca70)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffff80001020d728)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffff80001020e15c)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffff800010420550)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010423e6c)
Location: include/linux/sched/cputime.h:25
Inline: True
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
In kernel/exit.c (c03588a0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c0366fdc)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (c038f684)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (c03f96e0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (c040f19c)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (c044b3e4)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (c044c190)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c044cd70)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (c05e8850)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (c05e9514)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_prstatus
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000141e24)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c00000000015679c)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (c00000000018e720)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (c000000000212c24)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (c0000000002307f4)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (c00000000028a714)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (c00000000028b76c)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c00000000028c3fc)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (c00000000052f480)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (c0000000005330b0)
Location: include/linux/sched/cputime.h:25
Inline: True
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
In kernel/exit.c (ffffffe0000c48a0)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffe0000cf82c)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffe0000edb64)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000138162)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffe0001480ec)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffe00016dd86)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffe00016e77e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffffffe00016efbc)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffe0002c13e6)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e559)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810ad7d3)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810d9d97)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c8be)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffff81151294)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff8118cf85)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff8118dac0)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118e54b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff813534e2)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356d44)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void task_cputime(struct task_struct *t, u64 *utime, u64 *stime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8ac0)
Location: kernel/sched/cputime.c:862
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/acct.c:acct_collect
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
**Symbols:**

```
ffffffff810c8ac0-ffffffff810c8ba7: task_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e509)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810acd33)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810d60d7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a5de)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffff8114f144)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff8118ad55)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff8118b890)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118c31b)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81350fb2)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81354814)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6423)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b4f08)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sched/cputime.c (ffffffff810e19e7)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114709e)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/acct.c (ffffffff8115bf54)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/delayacct.c (ffffffff811986c5)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/taskstats.c (ffffffff81199205)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In kernel/tsacct.c (ffffffff81199cab)
Location: include/linux/sched/cputime.h:25
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_update_integrals
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/binfmt_elf.c (ffffffff81364555)
Location: include/linux/sched/cputime.h:25
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81367e3c)
Location: include/linux/sched/cputime.h:25
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
