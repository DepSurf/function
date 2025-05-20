# Function: <code>schedule_hrtimeout_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, long unsigned int delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff818239d0)
Location: kernel/time/hrtimer.c:1795
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/select.c:poll_schedule_timeout
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff818239d0-ffffffff818239e5: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8189e678)
Location: kernel/time/hrtimer.c:1755
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:poll_schedule_timeout
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8189e650-ffffffff8189e665: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff818d3518)
Location: kernel/time/hrtimer.c:1759
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:poll_schedule_timeout
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff818d34f0-ffffffff818d3505: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8190a6a8)
Location: kernel/time/hrtimer.c:1750
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:poll_schedule_timeout
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8190a680-ffffffff8190a695: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81994a08)
Location: kernel/time/hrtimer.c:1756
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:poll_schedule_timeout
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff819949e0-ffffffff819949f5: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff819f0fa5)
Location: kernel/time/hrtimer.c:1990
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff819f0f80-ffffffff819f0f95: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2c325)
Location: kernel/time/hrtimer.c:1980
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81a2c300-ffffffff81a2c315: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a9c4c5)
Location: kernel/time/hrtimer.c:1980
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81a9c4a0-ffffffff81a9c4b5: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3d15)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81ad3cf0-ffffffff81ad3d05: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81bcbd35)
Location: kernel/time/hrtimer.c:2179
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81bcbd10-ffffffff81bcbd25: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c44b58)
Location: kernel/time/hrtimer.c:2199
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81c44b30-ffffffff81c44b45: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37dc8)
Location: kernel/time/hrtimer.c:2199
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81c37da0-ffffffff81c37db5: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d56688)
Location: kernel/time/hrtimer.c:2347
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range_state
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81d56660-ffffffff81d56675: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81f284c8)
Location: kernel/time/hrtimer.c:2348
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range_state
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81f28490-ffffffff81f284b1: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820d4138)
Location: kernel/time/hrtimer.c:2350
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range_state
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff820d40f0-ffffffff820d4111: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff821583d8)
Location: kernel/time/hrtimer.c:2361
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range_state
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff82158390-ffffffff821583b1: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b248)
Location: kernel/time/hrtimer.c:2355
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range_state
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff8223b200-ffffffff8223b221: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff800010da68f4)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffff800010da6890-ffff800010da68d8: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0e9e704)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
c0e9e6bc-c0e9e6ec: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000ee9140)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
c000000000ee9110-c000000000ee9128: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe0008c8c7a)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/time/timer.c:usleep_range
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffe0008c8c24-ffffffe0008c8c60: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a72b85)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81a72b60-ffffffff81a72b75: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2ef55)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81a2ef30-ffffffff81a2ef45: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81adef95)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81adef70-ffffffff81adef85: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range(ktime_t *expires, u64 delta, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81aeb425)
Location: kernel/time/hrtimer.c:2172
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
Direct callers:
  - kernel/time/timer.c:usleep_range
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81aeb400-ffffffff81aeb415: schedule_hrtimeout_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int delta</code> ➡️ <code>u64 delta</code>
</li>
</ul>
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
