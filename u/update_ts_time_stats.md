# Function: <code>update_ts_time_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe130)
Location: kernel/time/tick-sched.c:440
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff810fe130-ffffffff810fe1b6: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811054c0)
Location: kernel/time/tick-sched.c:532
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff811054c0-ffffffff81105546: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110cc00)
Location: kernel/time/tick-sched.c:530
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff8110cc00-ffffffff8110cc86: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110eae0)
Location: kernel/time/tick-sched.c:540
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff8110eae0-ffffffff8110eb66: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81119d30)
Location: kernel/time/tick-sched.c:516
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff81119d30-ffffffff81119db6: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811268f0)
Location: kernel/time/tick-sched.c:509
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff811268f0-ffffffff81126966: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81131fd0)
Location: kernel/time/tick-sched.c:506
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff81131fd0-ffffffff81132046: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113ce10)
Location: kernel/time/tick-sched.c:515
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff8113ce10-ffffffff8113ce86: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811486c0)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff811486c0-ffffffff81148736: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811595a0)
Location: kernel/time/tick-sched.c:544
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81155560)
Location: kernel/time/tick-sched.c:592
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811568f3)
Location: kernel/time/tick-sched.c:593
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117b613)
Location: kernel/time/tick-sched.c:628
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b0c80)
Location: kernel/time/tick-sched.c:644
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f1860)
Location: kernel/time/tick-sched.c:644
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b4890)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
```
**Symbols:**

```
ffff8000101b4890-ffff8000101b4930: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03fedfc)
Location: kernel/time/tick-sched.c:519
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
c03fedfc-c03fef18: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c000000000219b90)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
c000000000219b90-c000000000219c60: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013ac30)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffe00013ac30-ffffffe00013acae: update_ts_time_stats (STB_LOCAL)
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
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81140ce0)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff81140ce0-ffffffff81140d56: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81133a80)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff81133a80-ffffffff81133af6: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113eb90)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff8113eb90-ffffffff8113ec06: update_ts_time_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_ts_time_stats(int cpu, struct tick_sched *ts, ktime_t now, u64 *last_update_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114b700)
Location: kernel/time/tick-sched.c:519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
**Symbols:**

```
ffffffff8114b700-ffffffff8114b776: update_ts_time_stats (STB_LOCAL)
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
