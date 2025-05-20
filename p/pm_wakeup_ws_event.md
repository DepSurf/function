# Function: <code>pm_wakeup_ws_event</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1dd0)
Location: drivers/base/power/wakeup.c:754
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff815f1dd0-ffffffff815f1e88: pm_wakeup_ws_event.part.14 (STB_LOCAL)
ffffffff815f1e90-ffffffff815f1eaa: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659380)
Location: drivers/base/power/wakeup.c:755
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff81659380-ffffffff81659438: pm_wakeup_ws_event.part.15 (STB_LOCAL)
ffffffff81659440-ffffffff8165945a: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695070)
Location: drivers/base/power/wakeup.c:754
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff81695070-ffffffff8169512a: pm_wakeup_ws_event.part.19 (STB_LOCAL)
ffffffff81695130-ffffffff81695149: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5710)
Location: drivers/base/power/wakeup.c:760
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff816b5710-ffffffff816b57ca: pm_wakeup_ws_event.part.19 (STB_LOCAL)
ffffffff816b57d0-ffffffff816b57e9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef2b0)
Location: drivers/base/power/wakeup.c:744
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff816ef2b0-ffffffff816ef36f: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff816ef370-ffffffff816ef389: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713410)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff81713410-ffffffff817134cf: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff817134d0-ffffffff817134e9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf210)
Location: drivers/base/power/wakeup.c:823
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff817cf210-ffffffff817cf30e: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff817cf310-ffffffff817cf329: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3810)
Location: drivers/base/power/wakeup.c:823
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff817e3810-ffffffff817e390e: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff817e3910-ffffffff817e3929: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c79d0)
Location: drivers/base/power/wakeup.c:824
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff817c79d0-ffffffff817c7ad6: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff817c7ae0-ffffffff817c7af9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851dd0)
Location: drivers/base/power/wakeup.c:825
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff81851dd0-ffffffff81851e93: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81851ea0-ffffffff81851eb9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997dc0)
Location: drivers/base/power/wakeup.c:825
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff81997dc0-ffffffff81997e8a: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81997e90-ffffffff81997ebd: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08ec0)
Location: drivers/base/power/wakeup.c:795
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff81b08ec0-ffffffff81b08f8a: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81b08fa0-ffffffff81b08fcd: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56ee0)
Location: drivers/base/power/wakeup.c:790
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff81b56ee0-ffffffff81b56faa: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81b56fc0-ffffffff81b56fed: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf4d0)
Location: drivers/base/power/wakeup.c:790
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
**Symbols:**

```
ffffffff81baf4d0-ffffffff81baf59a: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81baf5b0-ffffffff81baf5dd: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904568)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffff800010904568-ffff80001090467c: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffff800010904680-ffff8000109046c8: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee428)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
c09ee428-c09ee4f4: pm_wakeup_ws_event.part.0 (STB_LOCAL)
c09ee4f4-c09ee518: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2d20)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
c0000000009a2d20-c0000000009a2ed8: pm_wakeup_ws_event.part.0 (STB_LOCAL)
c0000000009a2ee0-c0000000009a2efc: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (0)
Location: include/linux/pm_wakeup.h:178
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9780)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff816d9780-ffffffff816d983f: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff816d9840-ffffffff816d9859: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3dd0)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff816b3dd0-ffffffff816b3e8f: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff816b3e90-ffffffff816b3ea9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817070d0)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff817070d0-ffffffff8170718f: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81707190-ffffffff817071a9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pm_wakeup_ws_event(struct wakeup_source *ws, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721b20)
Location: drivers/base/power/wakeup.c:764
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
**Symbols:**

```
ffffffff81721b20-ffffffff81721bdf: pm_wakeup_ws_event.part.0 (STB_LOCAL)
ffffffff81721be0-ffffffff81721bf9: pm_wakeup_ws_event (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
