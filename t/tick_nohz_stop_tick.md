# Function: <code>tick_nohz_stop_tick</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811271e3)
Location: kernel/time/tick-sched.c:732
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811328b4)
Location: kernel/time/tick-sched.c:729
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113d443)
Location: kernel/time/tick-sched.c:739
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
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
In kernel/time/tick-sched.c (ffffffff81148fe3)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811586f0)
Location: kernel/time/tick-sched.c:770
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811586f0-ffffffff811588a3: tick_nohz_stop_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154710)
Location: kernel/time/tick-sched.c:818
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81154710-ffffffff811548b4: tick_nohz_stop_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81155b90)
Location: kernel/time/tick-sched.c:819
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81155b90-ffffffff81155d34: tick_nohz_stop_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:854
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8117a800-ffffffff8117a9c3: tick_nohz_stop_tick (STB_LOCAL)
ffffffff81cb2148-ffffffff81cb2170: tick_nohz_stop_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:868
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811b0050-ffffffff811b025b: tick_nohz_stop_tick (STB_LOCAL)
ffffffff81e6369d-ffffffff81e636cf: tick_nohz_stop_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:868
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811f0af0-ffffffff811f0cfb: tick_nohz_stop_tick (STB_LOCAL)
ffffffff8205bd82-ffffffff8205bdb4: tick_nohz_stop_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:884
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81205510-ffffffff8120571f: tick_nohz_stop_tick (STB_LOCAL)
ffffffff820da592-ffffffff820da5c3: tick_nohz_stop_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:889
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8121bf70-ffffffff8121c17f: tick_nohz_stop_tick (STB_LOCAL)
ffffffff821b5fd2-ffffffff821b6003: tick_nohz_stop_tick.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b54a0)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03ff310)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
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
In kernel/time/tick-sched.c (c00000000021ab88)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
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
In kernel/time/tick-sched.c (ffffffe00013b69e)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81141603)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched *ts, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81134350)
Location: kernel/time/tick-sched.c:745
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81134350-ffffffff81134503: tick_nohz_stop_tick (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8113f4b3)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
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
In kernel/time/tick-sched.c (ffffffff8114bfc3)
Location: kernel/time/tick-sched.c:745
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Flavor</b>
<ul>
</ul>
