# Function: <code>sched_clock_tick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1490)
Location: kernel/sched/clock.c:317
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810b1490-ffffffff810b1506: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3f10)
Location: kernel/sched/clock.c:323
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810b3f10-ffffffff810b3f86: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba550)
Location: kernel/sched/clock.c:323
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810ba550-ffffffff810ba5c6: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4d90)
Location: kernel/sched/clock.c:381
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810b4d90-ffffffff810b4de2: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bc090)
Location: kernel/sched/clock.c:381
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810bc090-ffffffff810bc0d2: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c3720)
Location: kernel/sched/clock.c:369
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810c3720-ffffffff810c3762: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810cca10)
Location: kernel/sched/clock.c:388
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810cca10-ffffffff810cca4f: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4e00)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810d4e00-ffffffff810d4e40: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df3c0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810df3c0-ffffffff810df400: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e76b0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810e76b0-ffffffff810e76f2: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e52f0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810e52f0-ffffffff810e5332: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e72a0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810e72a0-ffffffff810e72e2: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe8d0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810fe8d0-ffffffff810fe90c: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145340)
Location: kernel/sched/clock.c:387
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81145340-ffffffff81145391: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81172420)
Location: kernel/sched/clock.c:387
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81172420-ffffffff81172471: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81183400)
Location: kernel/sched/clock.c:412
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81183400-ffffffff811834d6: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191b40)
Location: kernel/sched/clock.c:412
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81191b40-ffffffff81191c16: sched_clock_tick (STB_GLOBAL)
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
In kernel/sched/core.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched/clock.h:27
Inline: True
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
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d95b0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810d95b0-ffffffff810d95f0: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c7fa0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810c7fa0-ffffffff810c7fe0: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d58f0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810d58f0-ffffffff810d5930: sched_clock_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_tick();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e11e0)
Location: kernel/sched/clock.c:389
Inline: True
Direct callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810e11e0-ffffffff810e1220: sched_clock_tick (STB_GLOBAL)
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
