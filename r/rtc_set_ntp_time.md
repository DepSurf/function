# Function: <code>rtc_set_ntp_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff816733c0)
Location: drivers/rtc/systohc.c:23
Inline: False
```
**Symbols:**

```
ffffffff816733c0-ffffffff8167347a: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff816d3bb0)
Location: drivers/rtc/systohc.c:23
Inline: False
```
**Symbols:**

```
ffffffff816d3bb0-ffffffff816d3c6a: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff81703890)
Location: drivers/rtc/systohc.c:23
Inline: False
```
**Symbols:**

```
ffffffff81703890-ffffffff8170394a: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff81719070)
Location: drivers/rtc/systohc.c:23
Inline: False
```
**Symbols:**

```
ffffffff81719070-ffffffff8171912b: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff8178a250)
Location: drivers/rtc/systohc.c:26
Inline: False
```
**Symbols:**

```
ffffffff8178a250-ffffffff8178a389: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff817cb360)
Location: drivers/rtc/systohc.c:26
Inline: False
```
**Symbols:**

```
ffffffff817cb360-ffffffff817cb49c: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff817f2a10)
Location: drivers/rtc/systohc.c:26
Inline: False
```
**Symbols:**

```
ffffffff817f2a10-ffffffff817f2b4c: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff818336f0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff818336f0-ffffffff81833812: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff81865030)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff81865030-ffffffff81865152: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff81938880)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff81938880-ffffffff819389a2: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
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
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffff800010aa6890)
Location: drivers/rtc/systohc.c:21
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffff800010aa6890-ffff800010aa69bc: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (c0b8537c)
Location: drivers/rtc/systohc.c:21
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
c0b8537c-c0b854fc: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (c000000000b874a0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
c000000000b874a0-c000000000b87638: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffe0006b2bc2)
Location: drivers/rtc/systohc.c:21
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffe0006b2bc2-ffffffe0006b2cb2: rtc_set_ntp_time (STB_GLOBAL)
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
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff81817ce0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff81817ce0-ffffffff81817e02: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff817df3d0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff817df3d0-ffffffff817df4f2: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff818591c0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff818591c0-ffffffff818592e2: rtc_set_ntp_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtc_set_ntp_time(struct timespec64 now, long unsigned int *target_nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/systohc.c (ffffffff818742a0)
Location: drivers/rtc/systohc.c:21
Inline: False
```
**Symbols:**

```
ffffffff818742a0-ffffffff818743c2: rtc_set_ntp_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *target_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec now</code> ➡️ <code>struct timespec64 now</code>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
