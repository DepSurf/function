# Function: <code>can_stop_idle_tick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe6af)
Location: kernel/time/tick-sched.c:732
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105a3f)
Location: kernel/time/tick-sched.c:853
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110d18f)
Location: kernel/time/tick-sched.c:851
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110effe)
Location: kernel/time/tick-sched.c:864
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8111a01e)
Location: kernel/time/tick-sched.c:856
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:862
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81126cd0-ffffffff81126d59: can_stop_idle_tick.isra.13 (STB_LOCAL)
ffffffff81127a3b-ffffffff81127a53: can_stop_idle_tick.isra.13.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811323b0)
Location: kernel/time/tick-sched.c:859
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811323b0-ffffffff8113244d: can_stop_idle_tick.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113cd7f)
Location: kernel/time/tick-sched.c:867
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113cd10-ffffffff8113cd9b: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff8113dcc3-ffffffff8113dcdb: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148b1f)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81148ab0-ffffffff81148b3b: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff81149876-ffffffff8114988e: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:899
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81158950-ffffffff811589e3: can_stop_idle_tick (STB_LOCAL)
ffffffff811597e8-ffffffff81159800: can_stop_idle_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:947
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81154960-ffffffff811549f3: can_stop_idle_tick (STB_LOCAL)
ffffffff81be3d92-ffffffff81be3daa: can_stop_idle_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:948
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81155de0-ffffffff81155e73: can_stop_idle_tick (STB_LOCAL)
ffffffff81bd5cac-ffffffff81bd5cc4: can_stop_idle_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:987
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8117aa70-ffffffff8117ab03: can_stop_idle_tick (STB_LOCAL)
ffffffff81cb2170-ffffffff81cb2188: can_stop_idle_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b0320)
Location: kernel/time/tick-sched.c:1042
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811b0320-ffffffff811b03ae: can_stop_idle_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0df0)
Location: kernel/time/tick-sched.c:1042
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811f0df0-ffffffff811f0e7e: can_stop_idle_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205820)
Location: kernel/time/tick-sched.c:1058
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81205820-ffffffff812058e1: can_stop_idle_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:1061
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8121be50-ffffffff8121bf54: can_stop_idle_tick (STB_LOCAL)
ffffffff821b5fb6-ffffffff821b5fd2: can_stop_idle_tick.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b50b0)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffff8000101b50b0-ffff8000101b51c0: can_stop_idle_tick.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool can_stop_idle_tick(int cpu, struct tick_sched *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03fe548)
Location: kernel/time/tick-sched.c:874
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c03fe548-c03fe648: can_stop_idle_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (c00000000021a130)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
c00000000021a130-c00000000021a28c: can_stop_idle_tick.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013af4a)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffe00013af4a-ffffffe00013b046: can_stop_idle_tick.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114113f)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff811410d0-ffffffff8114115b: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff81141e96-ffffffff81141eae: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff81133e70-ffffffff81133f29: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff811351f6-ffffffff8113520e: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113efef)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8113ef80-ffffffff8113f00b: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff8113fd46-ffffffff8113fd5e: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114be6f)
Location: kernel/time/tick-sched.c:874
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff8114be00-ffffffff8114be8b: can_stop_idle_tick.isra.0 (STB_LOCAL)
ffffffff8114c876-ffffffff8114c88e: can_stop_idle_tick.isra.0.cold (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
