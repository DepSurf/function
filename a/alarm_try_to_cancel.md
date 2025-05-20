# Function: <code>alarm_try_to_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fb1d0)
Location: kernel/time/alarmtimer.c:367
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_del
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff810fb1d0-ffffffff810fb246: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811024d0)
Location: kernel/time/alarmtimer.c:382
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_del
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811024d0-ffffffff81102554: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81104d90)
Location: kernel/time/alarmtimer.c:413
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_del
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81104d90-ffffffff81104e71: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81106dc0)
Location: kernel/time/alarmtimer.c:388
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81106dc0-ffffffff81106e97: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81111ed0)
Location: kernel/time/alarmtimer.c:402
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81111ed0-ffffffff81111fb0: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111d760)
Location: kernel/time/alarmtimer.c:409
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
```
**Symbols:**

```
ffffffff8111d760-ffffffff8111d83f: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81129060)
Location: kernel/time/alarmtimer.c:406
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
```
**Symbols:**

```
ffffffff81129060-ffffffff8112913f: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81133ab0)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff81133ab0-ffffffff81133b96: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113fa80)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff8113fa80-ffffffff8113fb66: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114e510)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8114e510-ffffffff8114e5fc: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114a7a0)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8114a7a0-ffffffff8114a87a: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114bbb0)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8114bbb0-ffffffff8114bc8a: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116f8c0)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8116f8c0-ffffffff8116f9b5: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a3e10)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811a3e10-ffffffff811a3f25: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e36a0)
Location: kernel/time/alarmtimer.c:405
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811e36a0-ffffffff811e37b5: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f7d10)
Location: kernel/time/alarmtimer.c:404
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811f7d10-ffffffff811f7e25: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120deb0)
Location: kernel/time/alarmtimer.c:415
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8120deb0-ffffffff8120dfc5: alarm_try_to_cancel (STB_GLOBAL)
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
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a95c0)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffff8000101a95c0-ffff8000101a9754: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f4fe4)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
c03f4fe4-c03f5114: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020d230)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
c00000000020d230-c00000000020d3e8: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe0001352b0)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
ffffffe0001352b0-ffffffe0001353b2: alarm_try_to_cancel (STB_GLOBAL)
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
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81138230)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff81138230-ffffffff81138316: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112ac80)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff8112ac80-ffffffff8112ad66: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81135f50)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff81135f50-ffffffff81136036: alarm_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alarm_try_to_cancel(struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811429c0)
Location: kernel/time/alarmtimer.c:414
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_cancel
```
**Symbols:**

```
ffffffff811429c0-ffffffff81142abe: alarm_try_to_cancel (STB_GLOBAL)
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
