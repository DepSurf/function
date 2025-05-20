# Function: <code>__do_adjtimex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810f7410)
Location: kernel/time/ntp.c:715
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810f7410-ffffffff810f79cf: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810fe550)
Location: kernel/time/ntp.c:721
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810fe550-ffffffff810feb24: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81101340)
Location: kernel/time/ntp.c:721
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81101340-ffffffff81101914: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811034a0)
Location: kernel/time/ntp.c:721
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811034a0-ffffffff81103a60: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8110e530)
Location: kernel/time/ntp.c:721
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8110e530-ffffffff8110eaf0: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, struct timespec64 *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81119ee0)
Location: kernel/time/ntp.c:721
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81119ee0-ffffffff8111a4d7: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __do_adjtimex(struct timex *txc, const struct timespec64 *ts, s32 *time_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811253e0)
Location: kernel/time/ntp.c:710
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811253e0-ffffffff811259d7: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8112fe60)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8112fe60-ffffffff8113043a: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8113bda0)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8113bda0-ffffffff8113c37a: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8114b160)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8114b160-ffffffff8114b471: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81147610)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81147610-ffffffff81147921: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81148740)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81148740-ffffffff81148a6d: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8116c2f0)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8116c2f0-ffffffff8116c61d: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811a02f0)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811a02f0-ffffffff811a05de: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811df120)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811df120-ffffffff811df40e: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811f3600)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811f3600-ffffffff811f38f4: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81209740)
Location: kernel/time/ntp.c:762
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81209740-ffffffff81209a34: __do_adjtimex (STB_GLOBAL)
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
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffff8000101a6110)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffff8000101a6110-ffff8000101a6628: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c03f10fc)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
c03f10fc-c03f1950: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c000000000208310)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
c000000000208310-c000000000208a7c: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffe000132240)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffe000132240-ffffffe0001327f8: __do_adjtimex (STB_GLOBAL)
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
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81134550)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81134550-ffffffff81134b2a: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81126fb0)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81126fb0-ffffffff8112758a: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81132270)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81132270-ffffffff8113284a: __do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __do_adjtimex(struct __kernel_timex *txc, const struct timespec64 *ts, s32 *time_tai, struct audit_ntp_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8113ec90)
Location: kernel/time/ntp.c:714
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8113ec90-ffffffff8113f26a: __do_adjtimex (STB_GLOBAL)
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
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec64 *ts</code> ➡️ <code>const struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct audit_ntp_data *ad</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct timex *txc</code> ➡️ <code>struct __kernel_timex *txc</code>
</li>
</ul>
</details>
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
