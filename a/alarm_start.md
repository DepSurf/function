# Function: <code>alarm_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fa9d0)
Location: kernel/time/alarmtimer.c:320
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff810fa9d0-ffffffff810faa37: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81101c40)
Location: kernel/time/alarmtimer.c:335
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81101c40-ffffffff81101ca7: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81104330)
Location: kernel/time/alarmtimer.c:364
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81104330-ffffffff811043e8: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81106420)
Location: kernel/time/alarmtimer.c:339
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81106420-ffffffff811064d7: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811114a0)
Location: kernel/time/alarmtimer.c:353
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff811114a0-ffffffff8111155f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111ce90)
Location: kernel/time/alarmtimer.c:360
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff8111ce90-ffffffff8111cf4f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81128640)
Location: kernel/time/alarmtimer.c:357
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81128640-ffffffff811286ff: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81133080)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81133080-ffffffff8113313f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113efe0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff8113efe0-ffffffff8113f09f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114e870)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff8114e870-ffffffff8114e97c: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114aae0)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff8114aae0-ffffffff8114abe6: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114bfa0)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff8114bfa0-ffffffff8114c0a3: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116fd00)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff8116fd00-ffffffff8116fe1e: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a41f0)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff811a41f0-ffffffff811a4315: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e3ad0)
Location: kernel/time/alarmtimer.c:356
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff811e3ad0-ffffffff811e3bf5: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f8140)
Location: kernel/time/alarmtimer.c:355
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff811f8140-ffffffff811f8265: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120e2e0)
Location: kernel/time/alarmtimer.c:366
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:do_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff8120e2e0-ffffffff8120e405: alarm_start (STB_GLOBAL)
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
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a92e0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffff8000101a92e0-ffff8000101a944c: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f42ac)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
c03f42ac-c03f43dc: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020c0a0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
c00000000020c0a0-c00000000020c220: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134878)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - fs/timerfd.c:__se_sys_timerfd_settime
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffe000134878-ffffffe000134958: alarm_start (STB_GLOBAL)
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
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81137790)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
```
**Symbols:**

```
ffffffff81137790-ffffffff8113784f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112a1e0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
```
**Symbols:**

```
ffffffff8112a1e0-ffffffff8112a29f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811354b0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff811354b0-ffffffff8113556f: alarm_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void alarm_start(struct alarm *alarm, ktime_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81141ed0)
Location: kernel/time/alarmtimer.c:365
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_start_relative
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81141ed0-ffffffff81141f9d: alarm_start (STB_GLOBAL)
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
