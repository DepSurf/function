# Function: <code>alarm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fa930)
Location: kernel/time/alarmtimer.c:302
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff810fa930-ffffffff810fa986: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811027eb)
Location: kernel/time/alarmtimer.c:317
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81101ba0-ffffffff81101bf6: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8110510b)
Location: kernel/time/alarmtimer.c:346
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81104290-ffffffff811042e6: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81107142)
Location: kernel/time/alarmtimer.c:321
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81106390-ffffffff811063e0: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81112272)
Location: kernel/time/alarmtimer.c:335
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81111410-ffffffff81111460: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111d1f7)
Location: kernel/time/alarmtimer.c:346
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8111ce00-ffffffff8111ce50: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811289a7)
Location: kernel/time/alarmtimer.c:343
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff811285b0-ffffffff81128600: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811333f7)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81132ff0-ffffffff81133040: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113f347)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8113ef50-ffffffff8113efa0: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114efb0)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8114e160-ffffffff8114e1b3: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b2d0)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8114a3f0-ffffffff8114a443: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114c790)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8114b8b0-ffffffff8114b903: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811706d0)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8116f5b0-ffffffff8116f61f: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a4c8d)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff811a3a80-ffffffff811a3afb: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e458d)
Location: kernel/time/alarmtimer.c:342
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff811e3190-ffffffff811e320b: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f8bed)
Location: kernel/time/alarmtimer.c:341
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff811f77c0-ffffffff811f783b: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120ed8d)
Location: kernel/time/alarmtimer.c:352
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8120d960-ffffffff8120d9db: alarm_init (STB_GLOBAL)
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
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a90e0)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffff8000101a8ae0-ffff8000101a8b50: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f47ac)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c03f41f8-c03f425c: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020c674)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c00000000020bf50-c00000000020bfe4: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134c4c)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffe0001347bc-ffffffe000134828: alarm_init (STB_GLOBAL)
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
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81137af7)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
```
**Symbols:**

```
ffffffff81137700-ffffffff81137750: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112a547)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
```
**Symbols:**

```
ffffffff8112a150-ffffffff8112a1a0: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81135817)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81135420-ffffffff81135470: alarm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void alarm_init(struct alarm *alarm, enum alarmtimer_type type, enum alarmtimer_restart (*function)(struct alarm *, ktime_t));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81142247)
Location: kernel/time/alarmtimer.c:351
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81141e40-ffffffff81141e90: alarm_init (STB_GLOBAL)
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
