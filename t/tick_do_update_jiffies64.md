# Function: <code>tick_do_update_jiffies64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe360)
Location: kernel/time/tick-sched.c:52
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_do_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff810fe360-ffffffff810fe45e: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811056f0)
Location: kernel/time/tick-sched.c:52
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff811056f0-ffffffff811057ee: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110d7d8)
Location: kernel/time/tick-sched.c:52
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff8110cea0-ffffffff8110cf8f: tick_do_update_jiffies64.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110f6c8)
Location: kernel/time/tick-sched.c:56
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff8110ed80-ffffffff8110ee44: tick_do_update_jiffies64.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8111a9a8)
Location: kernel/time/tick-sched.c:57
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff8111a470-ffffffff8111a534: tick_do_update_jiffies64.part.10 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81127728)
Location: kernel/time/tick-sched.c:57
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff81126db0-ffffffff81126e74: tick_do_update_jiffies64.part.15 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81132e18)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff811324a0-ffffffff81132564: tick_do_update_jiffies64.part.16 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8113d9b8)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff8113d010-ffffffff8113d0e8: tick_do_update_jiffies64.part.0 (STB_LOCAL)
ffffffff8113dcdb-ffffffff8113dcfd: tick_do_update_jiffies64.part.0.cold (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81149558)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff81148bb0-ffffffff81148c71: tick_do_update_jiffies64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81158c62)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
**Symbols:**

```
ffffffff81158af0-ffffffff81158bb7: tick_do_update_jiffies64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154b00)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
```
**Symbols:**

```
ffffffff81154b00-ffffffff81154b9a: tick_do_update_jiffies64.part.0 (STB_LOCAL)
ffffffff81154ba0-ffffffff81154bf2: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811560f0)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811560f0-ffffffff811561cb: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117ada0)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff8117ada0-ffffffff8117ae7b: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811afd10)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_do_timer
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff811afd10-ffffffff811afe0d: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0750)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_do_timer
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff811f0750-ffffffff811f084d: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205170)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_do_timer
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff81205170-ffffffff8120526d: tick_do_update_jiffies64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tick_do_update_jiffies64(ktime_t now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121b840)
Location: kernel/time/tick-sched.c:57
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_do_timer
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff8121b840-ffffffff8121b93d: tick_do_update_jiffies64 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffff8000101b5b00)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffff8000101b4c20-ffff8000101b4d8c: tick_do_update_jiffies64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (c03ffac0)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
c03fe938-c03feac4: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (c00000000021b474)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
c00000000021a460-c00000000021a620: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffe00013bcf0)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffe00013b14e-ffffffe00013b2c2: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81141b78)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff811411d0-ffffffff81141291: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81134eda)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff81134040-ffffffff81134101: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8113fa28)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff8113f080-ffffffff8113f141: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8114c558)
Location: kernel/time/tick-sched.c:54
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
**Symbols:**

```
ffffffff8114baf0-ffffffff8114bbae: tick_do_update_jiffies64.part.0 (STB_LOCAL)
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
