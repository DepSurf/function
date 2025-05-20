# Function: <code>timekeeping_delta_to_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f554d)
Location: kernel/time/timekeeping.c:302
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff810fdc26)
Location: kernel/time/timekeeping.c:302
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff81100a16)
Location: kernel/time/timekeeping.c:301
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff81102b55)
Location: kernel/time/timekeeping.c:327
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8110daf8)
Location: kernel/time/timekeeping.c:346
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811194e1)
Location: kernel/time/timekeeping.c:347
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811249d1)
Location: kernel/time/timekeeping.c:353
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8112f315)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8113b2d5)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8114a325)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff81146875)
Location: kernel/time/timekeeping.c:372
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811479e5)
Location: kernel/time/timekeeping.c:372
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8116b50b)
Location: kernel/time/timekeeping.c:372
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8119f41b)
Location: kernel/time/timekeeping.c:374
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811de10b)
Location: kernel/time/timekeeping.c:374
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811f25db)
Location: kernel/time/timekeeping.c:374
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8120871b)
Location: kernel/time/timekeeping.c:374
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffff8000101a54e0)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (c03f0480)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (c0000000002072dc)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000131940)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
</details>
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
In kernel/time/timekeeping.c (ffffffff81133a85)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811264e5)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff811317a5)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
In kernel/time/timekeeping.c (ffffffff8113e1c5)
Location: kernel/time/timekeeping.c:359
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
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
</details>
</li>
</ul>

## Differences
