# Function: <code>alarm_forward_now</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fab10)
Location: kernel/time/alarmtimer.c:433
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff810fab10-ffffffff810fab46: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81101d80)
Location: kernel/time/alarmtimer.c:448
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81101d80-ffffffff81101db6: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81104530)
Location: kernel/time/alarmtimer.c:481
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81104530-ffffffff81104566: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811066ae)
Location: kernel/time/alarmtimer.c:456
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81106660-ffffffff81106693: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111174e)
Location: kernel/time/alarmtimer.c:470
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81111700-ffffffff81111739: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111d14f)
Location: kernel/time/alarmtimer.c:477
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8111d0f0-ffffffff8111d129: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112888f)
Location: kernel/time/alarmtimer.c:474
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81128830-ffffffff81128869: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113334f)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811332f0-ffffffff8113332b: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113f22f)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8113f1d0-ffffffff8113f20b: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114e9ef)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8114f4b0-ffffffff8114f535: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114ac5f)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8114b730-ffffffff8114b7b5: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114c11f)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8114cbe0-ffffffff8114cc65: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116fea2)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81170500-ffffffff8117059e: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a43b2)
Location: kernel/time/alarmtimer.c:473
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811a4a80-ffffffff811a4b2d: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e3cb2)
Location: kernel/time/alarmtimer.c:499
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811e4410-ffffffff811e44bd: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f8322)
Location: kernel/time/alarmtimer.c:498
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811f8a70-ffffffff811f8b1d: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120e4c2)
Location: kernel/time/alarmtimer.c:509
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8120ec10-ffffffff8120ecbd: alarm_forward_now (STB_GLOBAL)
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
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a94e0)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffff8000101a8c40-ffff8000101a8c94: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f4678)
Location: kernel/time/alarmtimer.c:482
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
c03f4678-c03f46d8: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020c4c8)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
c00000000020c410-c00000000020c480: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134afe)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffe000134a96-ffffffe000134ae4: alarm_forward_now (STB_GLOBAL)
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
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811379df)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff81137980-ffffffff811379bb: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112a42f)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff8112a3d0-ffffffff8112a40b: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811356ff)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811356a0-ffffffff811356db: alarm_forward_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward_now(struct alarm *alarm, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114212f)
Location: kernel/time/alarmtimer.c:482
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
**Symbols:**

```
ffffffff811420d0-ffffffff8114210b: alarm_forward_now (STB_GLOBAL)
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
