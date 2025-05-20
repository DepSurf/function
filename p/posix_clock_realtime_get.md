# Function: <code>posix_clock_realtime_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0d50)
Location: kernel/time/posix-timers.c:206
Inline: False
```
**Symbols:**

```
ffffffff810f0d50-ffffffff810f0d65: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7d70)
Location: kernel/time/posix-timers.c:206
Inline: False
```
**Symbols:**

```
ffffffff810f7d70-ffffffff810f7d85: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81105710)
Location: kernel/time/posix-timers.c:206
Inline: False
```
**Symbols:**

```
ffffffff81105710-ffffffff81105725: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811079f0)
Location: kernel/time/posix-timers.c:197
Inline: False
```
**Symbols:**

```
ffffffff811079f0-ffffffff81107a05: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112b60)
Location: kernel/time/posix-timers.c:198
Inline: False
```
**Symbols:**

```
ffffffff81112b60-ffffffff81112b75: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e620)
Location: kernel/time/posix-timers.c:198
Inline: False
```
**Symbols:**

```
ffffffff8111e620-ffffffff8111e635: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81129df0)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff81129df0-ffffffff81129e05: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81134870)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff81134870-ffffffff81134885: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81140880)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff81140880-ffffffff81140895: posix_clock_realtime_get (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101aac98)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffff8000101aac98-ffff8000101aacc8: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f6308)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
c03f6308-c03f632c: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020e950)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
c00000000020e950-c00000000020e98c: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000135fc8)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffe000135fc8-ffffffe000135ff4: posix_clock_realtime_get (STB_LOCAL)
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
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81139030)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff81139030-ffffffff81139045: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112ba80)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff8112ba80-ffffffff8112ba95: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136d50)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff81136d50-ffffffff81136d65: posix_clock_realtime_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_clock_realtime_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811437e0)
Location: kernel/time/posix-timers.c:168
Inline: False
```
**Symbols:**

```
ffffffff811437e0-ffffffff811437f5: posix_clock_realtime_get (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *tp</code> ➡️ <code>struct timespec64 *tp</code>
</li>
</ul>
</details>
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
