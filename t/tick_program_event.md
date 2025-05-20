# Function: <code>tick_program_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff810fdec0)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff810fdec0-ffffffff810fdf30: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81105250)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff81105250-ffffffff811052c0: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8110c9a0)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff8110c9a0-ffffffff8110ca10: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8110e880)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff8110e880-ffffffff8110e8f0: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81119b10)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff81119b10-ffffffff81119b84: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811266d0)
Location: kernel/time/tick-oneshot.c:27
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811266d0-ffffffff8112673f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81131db0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81131db0-ffffffff81131e1f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8113c8e0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113c8e0-ffffffff8113c95f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81148480)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81148480-ffffffff811484ff: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811582c0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff811582c0-ffffffff8115833f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81154360)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff81154360-ffffffff811543df: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811557d0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff811557d0-ffffffff8115584f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8117a440)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff8117a440-ffffffff8117a4bf: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811af900)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff811af900-ffffffff811af995: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811f0260)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff811f0260-ffffffff811f02f5: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff812049c0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
**Symbols:**

```
ffffffff812049c0-ffffffff81204a55: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8121af80)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_lowres_handler
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff8121af80-ffffffff8121b015: tick_program_event (STB_GLOBAL)
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
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffff8000101b4600)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffff8000101b4600-ffff8000101b46a0: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (c03fe234)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c03fe234-c03fe2e0: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (c000000000219830)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c000000000219830-c000000000219908: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffe00013a9aa)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffe00013a9aa-ffffffe00013aa44: tick_program_event (STB_GLOBAL)
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
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81140aa0)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81140aa0-ffffffff81140b1f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81133820)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
**Symbols:**

```
ffffffff81133820-ffffffff8113389f: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8113e950)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113e950-ffffffff8113e9cf: tick_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8114b460)
Location: kernel/time/tick-oneshot.c:23
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8114b460-ffffffff8114b4df: tick_program_event (STB_GLOBAL)
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
