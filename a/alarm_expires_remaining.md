# Function: <code>alarm_expires_remaining</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fa860)
Location: kernel/time/alarmtimer.c:202
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_get
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff810fa860-ffffffff810fa888: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81101ffe)
Location: kernel/time/alarmtimer.c:201
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_get
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81101ad0-ffffffff81101af8: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8110481e)
Location: kernel/time/alarmtimer.c:207
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_get
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81103e30-ffffffff81103e58: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81105f40)
Location: kernel/time/alarmtimer.c:214
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81105f40-ffffffff81105f65: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81110fc0)
Location: kernel/time/alarmtimer.c:228
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81110fc0-ffffffff81110feb: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111c9c0)
Location: kernel/time/alarmtimer.c:228
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8111c9c0-ffffffff8111c9eb: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81128170)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81128170-ffffffff8112819b: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81132bb0)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81132bb0-ffffffff81132bdb: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113eb00)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8113eb00-ffffffff8113eb2b: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114dd30)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8114dd30-ffffffff8114dd64: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81149fc0)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81149fc0-ffffffff81149ff4: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b480)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8114b480-ffffffff8114b4b4: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116f150)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8116f150-ffffffff8116f1a0: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a34e0)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff811a34e0-ffffffff811a353a: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e2b30)
Location: kernel/time/alarmtimer.c:225
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff811e2b30-ffffffff811e2b8a: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f7160)
Location: kernel/time/alarmtimer.c:224
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff811f7160-ffffffff811f71ba: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120d300)
Location: kernel/time/alarmtimer.c:224
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff8120d300-ffffffff8120d35a: alarm_expires_remaining (STB_GLOBAL)
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
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a8818)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffff8000101a8818-ffff8000101a8860: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f3cbc)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
c03f3cbc-c03f3cfc: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020b830)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
c00000000020b830-c00000000020b894: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134414)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffe000134414-ffffffe000134454: alarm_expires_remaining (STB_GLOBAL)
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
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811372b0)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
```
**Symbols:**

```
ffffffff811372b0-ffffffff811372db: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81129d00)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
```
**Symbols:**

```
ffffffff81129d00-ffffffff81129d2b: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81134fd0)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff81134fd0-ffffffff81134ffb: alarm_expires_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811419f0)
Location: kernel/time/alarmtimer.c:234
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_get_remaining
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
```
**Symbols:**

```
ffffffff811419f0-ffffffff81141a1b: alarm_expires_remaining (STB_GLOBAL)
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
