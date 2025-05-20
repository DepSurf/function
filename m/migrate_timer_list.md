# Function: <code>migrate_timer_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void migrate_timer_list(struct tvec_base *new_base, struct hlist_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec730)
Location: kernel/time/timer.c:1570
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_cpu_notify
  - kernel/time/timer.c:timer_cpu_notify
  - kernel/time/timer.c:timer_cpu_notify
  - kernel/time/timer.c:timer_cpu_notify
  - kernel/time/timer.c:timer_cpu_notify
```
**Symbols:**

```
ffffffff810ec730-ffffffff810ec7ec: migrate_timer_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f590e)
Location: kernel/time/timer.c:1797
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fc94e)
Location: kernel/time/timer.c:1802
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fed9e)
Location: kernel/time/timer.c:1793
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81109b1d)
Location: kernel/time/timer.c:1843
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81115134)
Location: kernel/time/timer.c:1854
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120774)
Location: kernel/time/timer.c:1853
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b060)
Location: kernel/time/timer.c:1857
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137000)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff81145ca5)
Location: kernel/time/timer.c:1966
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff811422c1)
Location: kernel/time/timer.c:1928
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff811434b1)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff81166a74)
Location: kernel/time/timer.c:1931
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff8119a198)
Location: kernel/time/timer.c:1985
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
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
In kernel/time/timer.c (ffffffff811d88a2)
Location: kernel/time/timer.c:2217
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eccd2)
Location: kernel/time/timer.c:2217
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202e2c)
Location: kernel/time/timer.c:2233
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff8000101a0320)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9f94)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000002012d0)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f7b0)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81122230)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d4d0)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139de7)
Location: kernel/time/timer.c:1945
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
