# Function: <code>clocksource_delta</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4315)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
```
```
In kernel/time/clocksource.c (ffffffff810f82c7)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fdbfc)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff810ff537)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811009ec)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811023a7)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81102b2b)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81104593)
Location: kernel/time/timekeeping_internal.h:16
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110dace)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8110f613)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811194c1)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8111b0a1)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811249b1)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81126bfe)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f2f5)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811315b2)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113b2b5)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8113d502)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114a305)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8114c68b)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146855)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81148aeb)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811479c5)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81149feb)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116b4e5)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8116dcf6)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119f3fe)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811a1eda)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811de0ee)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811e136a)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f25be)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811f58ca)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff812086fe)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff8120ba6a)
Location: kernel/time/timekeeping_internal.h:19
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a54e0)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffff8000101a70d4)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03f0480)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (c03f2168)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002072dc)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (c000000000209a70)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000131940)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffe00013310c)
Location: kernel/time/timekeeping_internal.h:28
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133a65)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81135cb2)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811264c5)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff81128702)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131785)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811339d2)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113e1a5)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/clocksource.c (ffffffff811403f2)
Location: kernel/time/timekeeping_internal.h:17
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
</ul>

## Differences
