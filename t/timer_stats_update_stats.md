# Function: <code>timer_stats_update_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void timer_stats_update_stats(void *timer, pid_t pid, void *startf, void *timerf, char *comm, u32 tflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_stats.c (ffffffff810ff4e0)
Location: kernel/time/timer_stats.c:235
Inline: False
Direct callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
**Symbols:**

```
ffffffff810ff4e0-ffffffff810ff6f8: timer_stats_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void timer_stats_update_stats(void *timer, pid_t pid, void *startf, void *timerf, char *comm, u32 tflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_stats.c (ffffffff81106840)
Location: kernel/time/timer_stats.c:235
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
**Symbols:**

```
ffffffff81106840-ffffffff81106ad3: timer_stats_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void timer_stats_update_stats(void *timer, pid_t pid, void *startf, void *timerf, char *comm, u32 tflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_stats.c (ffffffff8110dfd0)
Location: kernel/time/timer_stats.c:235
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
```
**Symbols:**

```
ffffffff8110dfd0-ffffffff8110e263: timer_stats_update_stats (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
