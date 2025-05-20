# Function: <code>nsec_to_clock_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eb510)
Location: kernel/time/time.c:682
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810eb510-ffffffff810eb532: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f21d0)
Location: kernel/time/time.c:689
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810f21d0-ffffffff810f21f2: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f9350)
Location: kernel/time/time.c:689
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810f9350-ffffffff810f9372: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb860)
Location: kernel/time/time.c:779
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff810fb860-ffffffff810fb882: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811061b0)
Location: kernel/time/time.c:746
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff811061b0-ffffffff811061d2: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811116f0)
Location: kernel/time/time.c:758
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff811116f0-ffffffff81111712: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ce00)
Location: kernel/time/time.c:696
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8111ce00-ffffffff8111ce22: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81127aa0)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81127aa0-ffffffff81127ac2: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81133a40)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81133a40-ffffffff81133a62: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142cd0)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81142cd0-ffffffff81142cf2: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113eee0)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff8113eee0-ffffffff8113ef02: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81140110)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff81140110-ffffffff81140132: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811635a0)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff811635a0-ffffffff811635c2: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81196600)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff81196600-ffffffff81196627: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d4620)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff811d4620-ffffffff811d4647: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8910)
Location: kernel/time/time.c:674
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff811e8910-ffffffff811e8937: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fe640)
Location: kernel/time/time.c:733
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
**Symbols:**

```
ffffffff811fe640-ffffffff811fe667: nsec_to_clock_t (STB_GLOBAL)
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
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019c100)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffff80001019c100-ffff80001019c13c: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5d14)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c03e5d14-c03e5d78: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fbbc0)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c0000000001fbbc0-c0000000001fbbe8: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012ac42)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffe00012ac42-ffffffe00012ac6e: nsec_to_clock_t (STB_GLOBAL)
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
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112c1f0)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8112c1f0-ffffffff8112c212: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ea60)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8111ea60-ffffffff8111ea82: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129f10)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81129f10-ffffffff81129f32: nsec_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 nsec_to_clock_t(u64 x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81136560)
Location: kernel/time/time.c:764
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81136560-ffffffff81136582: nsec_to_clock_t (STB_GLOBAL)
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
