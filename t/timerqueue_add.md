# Function: <code>timerqueue_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff813f21f0)
Location: lib/timerqueue.c:39
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff813f21f0-ffffffff813f2294: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81438b90)
Location: lib/timerqueue.c:39
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81438b90-ffffffff81438c34: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81455b80)
Location: lib/timerqueue.c:39
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81455b80-ffffffff81455c24: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff818f7460)
Location: lib/timerqueue.c:39
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff818f7460-ffffffff818f74e0: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8197de60)
Location: lib/timerqueue.c:40
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8197de60-ffffffff8197dee0: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff819da340)
Location: lib/timerqueue.c:40
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff819da340-ffffffff819da3c5: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a12560)
Location: lib/timerqueue.c:40
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a12560-ffffffff81a125e5: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a81a40)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a81a40-ffffffff81a81adf: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ab8c40)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ab8c40-ffffffff81ab8ce9: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815f38f0)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815f38f0-ffffffff815f398e: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81617f70)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81617f70-ffffffff8161800e: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815fb590)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815fb590-ffffffff815fb64a: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81668e60)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81668e60-ffffffff81668f1a: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff817828a0)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_initialize_alarm
```
**Symbols:**

```
ffffffff817828a0-ffffffff81782968: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8203f7d0)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_initialize_alarm
```
**Symbols:**

```
ffffffff8203f7d0-ffffffff8203f898: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff820bdcf0)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_initialize_alarm
```
**Symbols:**

```
ffffffff820bdcf0-ffffffff820bddb8: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff82198570)
Location: lib/timerqueue.c:35
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_initialize_alarm
```
**Symbols:**

```
ffffffff82198570-ffffffff82198638: timerqueue_add (STB_GLOBAL)
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
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffff800010d93218)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffff800010d93218-ffff800010d932d4: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c0e8f998)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c0e8f998-c0e8fa74: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c000000000ed7440)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c000000000ed7440-c000000000ed7548: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffe0008bd404)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffe0008bd404-ffffffe0008bd47a: timerqueue_add (STB_GLOBAL)
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
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a57a90)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a57a90-ffffffff81a57b39: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a14b70)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a14b70-ffffffff81a14c19: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ac3e80)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ac3e80-ffffffff81ac3f29: timerqueue_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool timerqueue_add(struct timerqueue_head *head, struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ad0350)
Location: lib/timerqueue.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/alarmtimer.c:alarmtimer_enqueue
  - kernel/time/posix-cpu-timers.c:arm_timer
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ad0350-ffffffff81ad03f9: timerqueue_add (STB_GLOBAL)
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
