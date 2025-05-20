# Function: <code>alarm_forward</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810faa80)
Location: kernel/time/alarmtimer.c:401
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_forward_now
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff810faa80-ffffffff810fab0d: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81101cf0)
Location: kernel/time/alarmtimer.c:416
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_forward_now
```
**Symbols:**

```
ffffffff81101cf0-ffffffff81101d77: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811044a0)
Location: kernel/time/alarmtimer.c:449
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_forward_now
```
**Symbols:**

```
ffffffff811044a0-ffffffff81104527: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811065f0)
Location: kernel/time/alarmtimer.c:424
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811065f0-ffffffff8110665a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81111690)
Location: kernel/time/alarmtimer.c:438
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81111690-ffffffff811116fa: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111d080)
Location: kernel/time/alarmtimer.c:445
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8111d080-ffffffff8111d0ea: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811287c0)
Location: kernel/time/alarmtimer.c:442
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811287c0-ffffffff8112882a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/alarmtimer.c (0)
Location: kernel/time/alarmtimer.c:441
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8113403e-ffffffff81134065: alarm_forward.cold (STB_LOCAL)
ffffffff81133270-ffffffff811332e9: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113f160)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8113f160-ffffffff8113f1ca: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114f1f3)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8114e1c0-ffffffff8114e22a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b6c3)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8114a450-ffffffff8114a4ba: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114cb73)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8114b910-ffffffff8114b97a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81170493)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
```
**Symbols:**

```
ffffffff8116f620-ffffffff8116f68a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a4a13)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
```
**Symbols:**

```
ffffffff811a3b00-ffffffff811a3b76: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e4393)
Location: kernel/time/alarmtimer.c:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811e3220-ffffffff811e3296: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f89f3)
Location: kernel/time/alarmtimer.c:440
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811f7850-ffffffff811f78c6: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120eb93)
Location: kernel/time/alarmtimer.c:451
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8120d9f0-ffffffff8120da66: alarm_forward (STB_GLOBAL)
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
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a8bb0)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffff8000101a8bb0-ffff8000101a8c3c: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f4580)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_forward_now
```
**Symbols:**

```
c03f4580-c03f4678: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020c360)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
c00000000020c360-c00000000020c410: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134a2a)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffe000134a2a-ffffffe000134a96: alarm_forward (STB_GLOBAL)
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
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81137910)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81137910-ffffffff8113797a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112a360)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8112a360-ffffffff8112a3ca: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81135630)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81135630-ffffffff8113569a: alarm_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 alarm_forward(struct alarm *alarm, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81142060)
Location: kernel/time/alarmtimer.c:450
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_timer_rearm
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81142060-ffffffff811420ca: alarm_forward (STB_GLOBAL)
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
