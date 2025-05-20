# Function: <code>timerqueue_iterate_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff813f22a0)
Location: lib/timerqueue.c:101
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff813f22a0-ffffffff813f22b3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81438c40)
Location: lib/timerqueue.c:101
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81438c40-ffffffff81438c53: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81455c30)
Location: lib/timerqueue.c:101
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81455c30-ffffffff81455c43: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff818f74e0)
Location: lib/timerqueue.c:100
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff818f74e0-ffffffff818f74f3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8197dee0)
Location: lib/timerqueue.c:102
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8197dee0-ffffffff8197def3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff819da3d0)
Location: lib/timerqueue.c:102
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff819da3d0-ffffffff819da3e3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a125f0)
Location: lib/timerqueue.c:102
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a125f0-ffffffff81a12603: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a81ae0)
Location: lib/timerqueue.c:89
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a81ae0-ffffffff81a81af3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ab8cf0)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ab8cf0-ffffffff81ab8d03: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815f3990)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815f3990-ffffffff815f39a3: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81618010)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81618010-ffffffff81618023: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff815fb650)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff815fb650-ffffffff815fb663: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81668f20)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81668f20-ffffffff81668f33: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81782970)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81782970-ffffffff8178298f: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff8203f8b0)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8203f8b0-ffffffff8203f8cf: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff820bddd0)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff820bddd0-ffffffff820bddef: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff82198650)
Location: lib/timerqueue.c:73
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff82198650-ffffffff8219866f: timerqueue_iterate_next (STB_GLOBAL)
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
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffff800010d932d8)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_active_timers
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffff800010d932d8-ffff800010d932f8: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c0e8fa74)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c0e8fa74-c0e8fa98: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (c000000000ed7550)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c000000000ed7550-c000000000ed7598: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffe0008bd47a)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffe0008bd47a-ffffffe0008bd498: timerqueue_iterate_next (STB_GLOBAL)
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
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a57b40)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a57b40-ffffffff81a57b53: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81a14c20)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81a14c20-ffffffff81a14c33: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ac3f30)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ac3f30-ffffffff81ac3f43: timerqueue_iterate_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timerqueue_node *timerqueue_iterate_next(struct timerqueue_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/timerqueue.c (ffffffff81ad0400)
Location: lib/timerqueue.c:83
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
  - kernel/time/timer_list.c:print_cpu
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81ad0400-ffffffff81ad0413: timerqueue_iterate_next (STB_GLOBAL)
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
