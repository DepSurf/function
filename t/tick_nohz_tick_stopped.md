# Function: <code>tick_nohz_tick_stopped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fea60)
Location: kernel/time/tick-sched.c:408
Inline: False
```
**Symbols:**

```
ffffffff810fea60-ffffffff810fea72: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105e00)
Location: kernel/time/tick-sched.c:500
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update_active
```
**Symbols:**

```
ffffffff81105e00-ffffffff81105e12: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110d540)
Location: kernel/time/tick-sched.c:498
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update_active
```
**Symbols:**

```
ffffffff8110d540-ffffffff8110d552: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110f400)
Location: kernel/time/tick-sched.c:508
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update_active
```
**Symbols:**

```
ffffffff8110f400-ffffffff8110f412: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8111a6c0)
Location: kernel/time/tick-sched.c:484
Inline: False
Direct callers:
  - kernel/sched/fair.c:cpu_load_update_active
```
**Symbols:**

```
ffffffff8111a6c0-ffffffff8111a6d2: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811270f0)
Location: kernel/time/tick-sched.c:468
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/fair.c:cpu_load_update_active
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff811270f0-ffffffff81127113: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811327e0)
Location: kernel/time/tick-sched.c:465
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/fair.c:cpu_load_update_active
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff811327e0-ffffffff81132803: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113d350)
Location: kernel/time/tick-sched.c:474
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8113d350-ffffffff8113d373: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148ef0)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81148ef0-ffffffff81148f13: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81159000)
Location: kernel/time/tick-sched.c:503
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81159000-ffffffff81159023: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154fe0)
Location: kernel/time/tick-sched.c:551
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81154fe0-ffffffff81155003: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81156350)
Location: kernel/time/tick-sched.c:552
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81156350-ffffffff81156373: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117b030)
Location: kernel/time/tick-sched.c:587
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8117b030-ffffffff8117b053: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b0660)
Location: kernel/time/tick-sched.c:603
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/irq_work.c:__irq_work_queue_local
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff811b0660-ffffffff811b0687: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f1170)
Location: kernel/time/tick-sched.c:603
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/irq_work.c:__irq_work_queue_local
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff811f1170-ffffffff811f1197: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205960)
Location: kernel/time/tick-sched.c:624
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81205960-ffffffff81205986: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121cb00)
Location: kernel/time/tick-sched.c:625
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8121cb00-ffffffff8121cb26: tick_nohz_tick_stopped (STB_GLOBAL)
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
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b5388)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffff8000101b5388-ffff8000101b53b8: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03ff1f8)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
c03ff1f8-c03ff228: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c00000000021aa50)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
c00000000021aa50-c00000000021aa7c: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013b5b8)
Location: kernel/time/tick-sched.c:478
Inline: False
```
**Symbols:**

```
ffffffe00013b5b8-ffffffe00013b5f6: tick_nohz_tick_stopped (STB_GLOBAL)
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
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81141510)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81141510-ffffffff81141533: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81134960)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81134960-ffffffff81134983: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113f3c0)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff8113f3c0-ffffffff8113f3e3: tick_nohz_tick_stopped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tick_nohz_tick_stopped();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114bed0)
Location: kernel/time/tick-sched.c:478
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff8114bed0-ffffffff8114bef3: tick_nohz_tick_stopped (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
