# Function: <code>ktime_get_coarse_ts64</code>

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
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117850)
Location: kernel/time/timekeeping.c:2149
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff81117850-ffffffff811178a4: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122e70)
Location: kernel/time/timekeeping.c:2163
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff81122e70-ffffffff81122ec4: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d650)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff8112d650-ffffffff8112d6a1: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811395c0)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff811395c0-ffffffff81139611: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148270)
Location: kernel/time/timekeeping.c:2172
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff81148270-ffffffff811482c5: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811446b0)
Location: kernel/time/timekeeping.c:2235
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff811446b0-ffffffff81144705: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145830)
Location: kernel/time/timekeeping.c:2246
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff81145830-ffffffff81145885: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2247
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff81cb0c6c-ffffffff81cb0c8c: ktime_get_coarse_ts64.cold (STB_LOCAL)
ffffffff81169730-ffffffff8116979d: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2268
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff81e62204-ffffffff81e62224: ktime_get_coarse_ts64.cold (STB_LOCAL)
ffffffff8119d400-ffffffff8119d47b: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2268
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff8205b051-ffffffff8205b071: ktime_get_coarse_ts64.cold (STB_LOCAL)
ffffffff811dbf20-ffffffff811dbf9b: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2268
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff820d98a3-ffffffff820d98c3: ktime_get_coarse_ts64.cold (STB_LOCAL)
ffffffff811f01c0-ffffffff811f023b: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2268
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
**Symbols:**

```
ffffffff821b51a2-ffffffff821b51c2: ktime_get_coarse_ts64.cold (STB_LOCAL)
ffffffff81206300-ffffffff8120637b: ktime_get_coarse_ts64 (STB_GLOBAL)
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
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3358)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffff8000101a3358-ffff8000101a33cc: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed3e8)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
c03ed3e8-c03ed4b0: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204c10)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
c000000000204c10-c000000000204c9c: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012ff94)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffe00012ff94-ffffffe00012fffa: ktime_get_coarse_ts64 (STB_GLOBAL)
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
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131d70)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff81131d70-ffffffff81131dc1: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811247d0)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff811247d0-ffffffff81124821: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112fa90)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff8112fa90-ffffffff8112fae1: ktime_get_coarse_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ktime_get_coarse_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c4b0)
Location: kernel/time/timekeeping.c:2173
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff8113c4b0-ffffffff8113c501: ktime_get_coarse_ts64 (STB_GLOBAL)
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
