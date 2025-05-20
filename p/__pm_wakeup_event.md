# Function: <code>__pm_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pm_wakeup_event(struct wakeup_source *ws, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c2a0)
Location: drivers/base/power/wakeup.c:755
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/base/power/wakeup.c:pm_wakeup_event
```
**Symbols:**

```
ffffffff8155c2a0-ffffffff8155c355: __pm_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pm_wakeup_event(struct wakeup_source *ws, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae4a0)
Location: drivers/base/power/wakeup.c:753
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/base/power/wakeup.c:pm_wakeup_event
```
**Symbols:**

```
ffffffff815ae4a0-ffffffff815ae555: __pm_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pm_wakeup_event(struct wakeup_source *ws, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd2a0)
Location: drivers/base/power/wakeup.c:753
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/base/power/wakeup.c:pm_wakeup_event
```
**Symbols:**

```
ffffffff815dd2a0-ffffffff815dd355: __pm_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff810e0dfe)
Location: include/linux/pm_wakeup.h:206
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81106ad9)
Location: include/linux/pm_wakeup.h:206
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff810e90ce)
Location: include/linux/pm_wakeup.h:206
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81111b85)
Location: include/linux/pm_wakeup.h:206
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff810f13e8)
Location: include/linux/pm_wakeup.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff8111d619)
Location: include/linux/pm_wakeup.h:213
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff810fca78)
Location: include/linux/pm_wakeup.h:213
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81128dc9)
Location: include/linux/pm_wakeup.h:213
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81105191)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81133819)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81111531)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff8113f769)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff8111c601)
Location: include/linux/pm_wakeup.h:195
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81116f61)
Location: include/linux/pm_wakeup.h:205
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff819a9815)
Location: include/linux/pm_wakeup.h:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81117688)
Location: include/linux/pm_wakeup.h:205
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff8198e1c5)
Location: include/linux/pm_wakeup.h:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff811379e8)
Location: include/linux/pm_wakeup.h:205
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff81a39855)
Location: include/linux/pm_wakeup.h:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff8115a09a)
Location: include/linux/pm_wakeup.h:205
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff81ba6713)
Location: include/linux/pm_wakeup.h:205
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff8118c36a)
Location: include/linux/pm_wakeup.h:197
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff81d48c63)
Location: include/linux/pm_wakeup.h:197
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff8119da8a)
Location: include/linux/pm_wakeup.h:197
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff81db2843)
Location: include/linux/pm_wakeup.h:197
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff811acbfa)
Location: include/linux/pm_wakeup.h:207
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/mmc/core/core.c (ffffffff81e6abd3)
Location: include/linux/pm_wakeup.h:207
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffff8000101719bc)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffff8000101aa3bc)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (c03c4358)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (c03f4bcc)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (c0000000001ca144)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (c00000000020cd20)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
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
Location: include/linux/pm_wakeup.h:186
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81109b11)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81137f19)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff810fa9f1)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff8112a969)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81107a01)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81135c39)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/wakelock.c (ffffffff81112db1)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/time/alarmtimer.c (ffffffff81142682)
Location: include/linux/pm_wakeup.h:186
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
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
</ul>
