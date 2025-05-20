# Function: <code>get_target_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8182340c)
Location: kernel/time/timer.c:137
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff810ef4cc)
Location: kernel/time/hrtimer.c:182
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189df00)
Location: kernel/time/timer.c:921
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810f655f)
Location: kernel/time/hrtimer.c:182
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2d78)
Location: kernel/time/timer.c:881
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810fd582)
Location: kernel/time/hrtimer.c:182
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909f5c)
Location: kernel/time/timer.c:847
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810ff8cf)
Location: kernel/time/hrtimer.c:183
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8199428c)
Location: kernel/time/timer.c:854
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff8110a6e4)
Location: kernel/time/hrtimer.c:183
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f0804)
Location: kernel/time/timer.c:870
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81115b97)
Location: kernel/time/hrtimer.c:203
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2bb84)
Location: kernel/time/timer.c:869
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff811216a7)
Location: kernel/time/hrtimer.c:194
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a9bdb5)
Location: kernel/time/timer.c:864
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff8112bf41)
Location: kernel/time/hrtimer.c:193
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ad3705)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81137f40)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811446c4)
Location: kernel/time/timer.c:876
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff81146aec)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141ada)
Location: kernel/time/timer.c:880
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff81142c1c)
Location: kernel/time/hrtimer.c:202
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811428c3)
Location: kernel/time/timer.c:882
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff8114414a)
Location: kernel/time/hrtimer.c:202
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81165db3)
Location: kernel/time/timer.c:882
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff811679e1)
Location: kernel/time/hrtimer.c:202
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199996)
Location: kernel/time/timer.c:935
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff8119b38a)
Location: kernel/time/hrtimer.c:202
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7fe9)
Location: kernel/time/timer.c:935
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff811d9bfa)
Location: kernel/time/hrtimer.c:202
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec493)
Location: kernel/time/timer.c:935
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff811edd14)
Location: kernel/time/hrtimer.c:203
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff812024b7)
Location: kernel/time/timer.c:932
Inline: True
Inline callers:
  - kernel/time/timer.c:__mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff81204074)
Location: kernel/time/hrtimer.c:203
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f300)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffff8000101a1764)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0e9dfe4)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (c03eb3c0)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000ee89b4)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (c000000000202d00)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe0008c86f8)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffe00012ecc6)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a72575)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff811306f0)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2e945)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81123160)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ade985)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff8112e410)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81aeae05)
Location: kernel/time/timer.c:868
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff8113adf0)
Location: kernel/time/hrtimer.c:198
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>

## Differences
