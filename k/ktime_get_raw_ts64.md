# Function: <code>ktime_get_raw_ts64</code>

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
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118420)
Location: kernel/time/timekeeping.c:1418
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81118420-ffffffff811184e7: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123a40)
Location: kernel/time/timekeeping.c:1409
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81123a40-ffffffff81123b07: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112e940)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff8112e940-ffffffff8112ea07: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113a990)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff8113a990-ffffffff8113aa57: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81149690)
Location: kernel/time/timekeeping.c:1418
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81149690-ffffffff81149759: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145f60)
Location: kernel/time/timekeeping.c:1486
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81145f60-ffffffff81146024: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146a40)
Location: kernel/time/timekeeping.c:1497
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81146a40-ffffffff81146b04: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1496
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81cb0d9a-ffffffff81cb0dbe: ktime_get_raw_ts64.cold (STB_LOCAL)
ffffffff81169c50-ffffffff81169d1f: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1517
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81e62301-ffffffff81e62325: ktime_get_raw_ts64.cold (STB_LOCAL)
ffffffff8119d850-ffffffff8119d91f: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1517
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff8205b172-ffffffff8205b196: ktime_get_raw_ts64.cold (STB_LOCAL)
ffffffff811dc4d0-ffffffff811dc59f: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1517
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff820d9a06-ffffffff820d9a2a: ktime_get_raw_ts64.cold (STB_LOCAL)
ffffffff811f08e0-ffffffff811f09af: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1517
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff821b5305-ffffffff821b5329: ktime_get_raw_ts64.cold (STB_LOCAL)
ffffffff81206a20-ffffffff81206aef: ktime_get_raw_ts64 (STB_GLOBAL)
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
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2ce0)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffff8000101a2ce0-ffff8000101a2dc4: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ec948)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - sound/core/pcm_native.c:snd_pcm_trigger_tstamp
  - sound/core/pcm_native.c:snd_pcm_status
  - sound/core/pcm_lib.c:update_audio_tstamp
  - sound/core/pcm_lib.c:__snd_pcm_xrun
```
**Symbols:**

```
c03ec948-c03ecac4: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204200)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
c000000000204200-c00000000020430c: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fa02)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffe00012fa02-ffffffe00012fab0: ktime_get_raw_ts64 (STB_GLOBAL)
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
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133140)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81133140-ffffffff81133207: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125ba0)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81125ba0-ffffffff81125c67: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130e60)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff81130e60-ffffffff81130f27: ktime_get_raw_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ktime_get_raw_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113d880)
Location: kernel/time/timekeeping.c:1419
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
```
**Symbols:**

```
ffffffff8113d880-ffffffff8113d947: ktime_get_raw_ts64 (STB_GLOBAL)
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
