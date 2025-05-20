# Function: <code>tick_nohz_next_event</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81126af0)
Location: kernel/time/tick-sched.c:648
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81126af0-ffffffff81126c6a: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811321d0)
Location: kernel/time/tick-sched.c:645
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811321d0-ffffffff8113234a: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113cb20)
Location: kernel/time/tick-sched.c:654
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113cb20-ffffffff8113cca1: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811488c0)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811488c0-ffffffff81148a41: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81158500)
Location: kernel/time/tick-sched.c:685
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81158500-ffffffff81158683: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154530)
Location: kernel/time/tick-sched.c:733
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81154530-ffffffff811546ac: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811559b0)
Location: kernel/time/tick-sched.c:734
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811559b0-ffffffff81155b26: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117a620)
Location: kernel/time/tick-sched.c:769
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8117a620-ffffffff8117a796: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811afb60)
Location: kernel/time/tick-sched.c:785
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811afb60-ffffffff811afc9a: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0580)
Location: kernel/time/tick-sched.c:785
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811f0580-ffffffff811f06ba: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81204d10)
Location: kernel/time/tick-sched.c:801
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81204d10-ffffffff81204e48: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121b3e0)
Location: kernel/time/tick-sched.c:802
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8121b3e0-ffffffff8121b51f: tick_nohz_next_event (STB_LOCAL)
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
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b51c0)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffff8000101b51c0-ffff8000101b5344: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03fe648)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c03fe648-c03fe88c: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c000000000219f20)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c000000000219f20-c00000000021a124: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013adf2)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffe00013adf2-ffffffe00013af4a: tick_nohz_next_event (STB_LOCAL)
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
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81140ee0)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81140ee0-ffffffff81141061: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81133c80)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81133c80-ffffffff81133e01: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113ed90)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113ed90-ffffffff8113ef11: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t tick_nohz_next_event(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114b900)
Location: kernel/time/tick-sched.c:660
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8114b900-ffffffff8114ba81: tick_nohz_next_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
