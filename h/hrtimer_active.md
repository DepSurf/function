# Function: <code>hrtimer_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eea10)
Location: kernel/time/hrtimer.c:1170
Inline: False
Direct callers:
  - kernel/sched/core.c:hotplug_hrtick
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/posix-timers.c:common_timer_get
```
**Symbols:**

```
ffffffff810eea10-ffffffff810eea62: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5b10)
Location: kernel/time/hrtimer.c:1160
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/posix-timers.c:common_timer_get
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff810f5b10-ffffffff810f5b62: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcad0)
Location: kernel/time/hrtimer.c:1160
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/itimer.c:itimer_get_remtime
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff810fcad0-ffffffff810fcb22: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff020)
Location: kernel/time/hrtimer.c:1136
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - block/cfq-iosched.c:cfq_dispatch_requests
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff810ff020-ffffffff810ff070: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109e00)
Location: kernel/time/hrtimer.c:1141
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - block/cfq-iosched.c:cfq_dispatch_requests
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81109e00-ffffffff81109e50: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811153d0)
Location: kernel/time/hrtimer.c:1320
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - block/cfq-iosched.c:cfq_dispatch_requests
```
**Symbols:**

```
ffffffff811153d0-ffffffff8111541a: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120a10)
Location: kernel/time/hrtimer.c:1311
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81120a10-ffffffff81120a5a: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b240)
Location: kernel/time/hrtimer.c:1311
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8112b240-ffffffff8112b28c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137320)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81137320-ffffffff8113736c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81145fb0)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff81145fb0-ffffffff81145ffe: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811424d0)
Location: kernel/time/hrtimer.c:1456
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - drivers/mailbox/mailbox.c:msg_submit
```
**Symbols:**

```
ffffffff811424d0-ffffffff81142514: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811436b0)
Location: kernel/time/hrtimer.c:1456
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - drivers/mailbox/mailbox.c:msg_submit
```
**Symbols:**

```
ffffffff811436b0-ffffffff811436f4: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166c90)
Location: kernel/time/hrtimer.c:1604
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - drivers/mailbox/mailbox.c:msg_submit
```
**Symbols:**

```
ffffffff81166c90-ffffffff81166cd4: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a430)
Location: kernel/time/hrtimer.c:1604
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff8119a430-ffffffff8119a488: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8b60)
Location: kernel/time/hrtimer.c:1604
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff811d8b60-ffffffff811d8bb8: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ecf90)
Location: kernel/time/hrtimer.c:1607
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff811ecf90-ffffffff811ecfe8: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff812030f0)
Location: kernel/time/hrtimer.c:1608
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff812030f0-ffffffff81203148: hrtimer_active (STB_GLOBAL)
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
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0778)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffff8000101a0778-ffff8000101a080c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea2d0)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c03ea2d0-c03ea388: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201680)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c000000000201680-c000000000201708: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e0a2)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffe00012e0a2-ffffffe00012e116: hrtimer_active (STB_GLOBAL)
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
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fad0)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8112fad0-ffffffff8112fb1c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122540)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff81122540-ffffffff8112258c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d7f0)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8112d7f0-ffffffff8112d83c: hrtimer_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a120)
Location: kernel/time/hrtimer.c:1439
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/rt.c:sched_rt_bandwidth_account
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:task_non_contending
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113a120-ffffffff8113a16c: hrtimer_active (STB_GLOBAL)
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
