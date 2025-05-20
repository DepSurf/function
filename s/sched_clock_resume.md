# Function: <code>sched_clock_resume</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
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
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
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
void sched_clock_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffff8000101b4490)
Location: kernel/time/sched_clock.c:288
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_unfreeze
```
**Symbols:**

```
ffff8000101b4490-ffff8000101b44e8: sched_clock_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_clock_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (c03fe07c)
Location: kernel/time/sched_clock.c:288
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_unfreeze
```
**Symbols:**

```
c03fe07c-c03fe0e4: sched_clock_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_clock_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffffffe00013a85c)
Location: kernel/time/sched_clock.c:288
Inline: False
```
**Symbols:**

```
ffffffe00013a85c-ffffffe00013a8a4: sched_clock_resume (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-common.c (0)
Location: kernel/time/timekeeping.h:22
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
