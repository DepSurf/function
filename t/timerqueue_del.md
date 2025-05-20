# Function: <code>timerqueue_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff813f22c0)
Location: lib/timerqueue.c:75
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff813f22c0-ffffffff813f2327: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81438c60)
Location: lib/timerqueue.c:75
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81438c60-ffffffff81438cc7: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81455c50)
Location: lib/timerqueue.c:75
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81455c50-ffffffff81455cb7: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff818f7500)
Location: lib/timerqueue.c:75
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff818f7500-ffffffff818f7548: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8197df00)
Location: lib/timerqueue.c:77
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8197df00-ffffffff8197df48: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff819da3f0)
Location: lib/timerqueue.c:77
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff819da3f0-ffffffff819da438: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a12610)
Location: lib/timerqueue.c:77
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a12610-ffffffff81a12658: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a81b00)
Location: lib/timerqueue.c:64
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a81b00-ffffffff81a81b48: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ab8d10)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ab8d10-ffffffff81ab8d59: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815f39b0)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815f39b0-ffffffff815f39f9: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81618030)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__run_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81618030-ffffffff81618079: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815fb670)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815fb670-ffffffff815fb6b7: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81668f40)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81668f40-ffffffff81668f87: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81782990)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/class.c:rtc_device_release
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81782990-ffffffff817829df: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8203f8e0)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/class.c:rtc_device_release
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8203f8e0-ffffffff8203f92f: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff820bde00)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/class.c:rtc_device_release
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff820bde00-ffffffff820bde4f: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff82198680)
Location: lib/timerqueue.c:53
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/class.c:rtc_device_release
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff82198680-ffffffff821986cf: timerqueue_del (STB_GLOBAL)
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
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffff800010d932f8)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffff800010d932f8-ffff800010d93364: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c0e8fa98)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c0e8fa98-c0e8fb28: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c000000000ed75a0)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c000000000ed75a0-c000000000ed7678: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffe0008bd498)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffe0008bd498-ffffffe0008bd4ec: timerqueue_del (STB_GLOBAL)
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
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a57b60)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a57b60-ffffffff81a57ba9: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a14c40)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a14c40-ffffffff81a14c89: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ac3f50)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ac3f50-ffffffff81ac3f99: timerqueue_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ad0420)
Location: lib/timerqueue.c:63
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:collect_posix_cputimers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ad0420-ffffffff81ad0469: timerqueue_del (STB_GLOBAL)
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
