# Function: <code>timekeeping_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4be0)
Location: kernel/time/timekeeping.c:579
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810f4be0-ffffffff810f4d2a: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fbda0)
Location: kernel/time/timekeeping.c:584
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810fbda0-ffffffff810fbeea: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810feca0)
Location: kernel/time/timekeeping.c:613
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810feca0-ffffffff810fedea: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100f70)
Location: kernel/time/timekeeping.c:644
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff81100f70-ffffffff81101085: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110bd90)
Location: kernel/time/timekeeping.c:647
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8110bd90-ffffffff8110beba: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117940)
Location: kernel/time/timekeeping.c:648
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81117940-ffffffff81117a67: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122f60)
Location: kernel/time/timekeeping.c:655
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81122f60-ffffffff81123087: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d740)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112d740-ffffffff8112d867: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811396b0)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811396b0-ffffffff811397d7: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811488d0)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811488d0-ffffffff811489f8: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144d40)
Location: kernel/time/timekeeping.c:738
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81144d40-ffffffff81144e68: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145c30)
Location: kernel/time/timekeeping.c:738
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81145c30-ffffffff81145d58: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:738
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81169380-ffffffff811694c3: timekeeping_update (STB_LOCAL)
ffffffff81cb0bca-ffffffff81cb0be6: timekeeping_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:757
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8119cfe0-ffffffff8119d131: timekeeping_update (STB_LOCAL)
ffffffff81e62162-ffffffff81e6217e: timekeeping_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:757
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff811dba90-ffffffff811dbbe1: timekeeping_update (STB_LOCAL)
ffffffff8205afaf-ffffffff8205afcb: timekeeping_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:757
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff811effd0-ffffffff811f0121: timekeeping_update (STB_LOCAL)
ffffffff820d9867-ffffffff820d9883: timekeeping_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:757
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff81206110-ffffffff81206261: timekeeping_update (STB_LOCAL)
ffffffff821b5166-ffffffff821b5182: timekeeping_update.cold (STB_LOCAL)
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
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3468)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffff8000101a3468-ffff8000101a3598: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed540)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c03ed540-c03ed6d8: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204d50)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c000000000204d50-c000000000204ef4: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130092)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffe000130092-ffffffe0001301c2: timekeeping_update (STB_LOCAL)
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
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131e60)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81131e60-ffffffff81131f87: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811248c0)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811248c0-ffffffff811249e7: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112fb80)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112fb80-ffffffff8112fca7: timekeeping_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void timekeeping_update(struct timekeeper *tk, unsigned int action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c5a0)
Location: kernel/time/timekeeping.c:661
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8113c5a0-ffffffff8113c6c7: timekeeping_update (STB_LOCAL)
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
