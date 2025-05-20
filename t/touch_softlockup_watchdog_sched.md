# Function: <code>touch_softlockup_watchdog_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81142cb1)
Location: kernel/watchdog.c:237
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_nmi_watchdog
Direct callers:
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff811435c0-ffffffff811435d7: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ca96)
Location: kernel/watchdog.c:177
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/sched/clock.c:sched_clock_idle_wakeup_event
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff8114cfd0-ffffffff8114cfe7: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ea16)
Location: kernel/watchdog.c:260
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff8114f140-ffffffff8114f157: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8115b2a6)
Location: kernel/watchdog.c:269
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff8115b960-ffffffff8115b977: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81169eb0)
Location: kernel/watchdog.c:269
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff8116a4b0-ffffffff8116a4c2: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81176db0)
Location: kernel/watchdog.c:264
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811774c0-ffffffff811774d2: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81183c10)
Location: kernel/watchdog.c:271
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811842a0-ffffffff811842ad: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8118fa80)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81190120-ffffffff8119012d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a4640)
Location: kernel/watchdog.c:252
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811a4ca0-ffffffff811a4cad: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a16e0)
Location: kernel/watchdog.c:252
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811a1d40-ffffffff811a1d4d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a2340)
Location: kernel/watchdog.c:264
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811a2a30-ffffffff811a2a3d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811cbb20)
Location: kernel/watchdog.c:264
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff811cc200-ffffffff811cc20d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811ff8a0)
Location: kernel/watchdog.c:264
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff812001f0-ffffffff81200201: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff812472d0)
Location: kernel/watchdog.c:264
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81247d50-ffffffff81247d61: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8125e380)
Location: kernel/watchdog.c:364
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff8125f170-ffffffff8125f181: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff812782c0)
Location: kernel/watchdog.c:391
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_update_jiffies
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81279180-ffffffff81279191: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffff8000102071b0)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffff8000102079f8-ffff800010207a10: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c0446784)
Location: kernel/watchdog.c:273
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
c0446784-c04467a8: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c000000000283758)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
**Symbols:**

```
c0000000002842a0-c0000000002842c0: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffe00016a120)
Location: kernel/watchdog.c:273
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffe00016a120-ffffffe00016a14e: touch_softlockup_watchdog_sched (STB_GLOBAL)
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
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811880a0)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81188740-ffffffff8118874d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8117b1e0)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff8117b880-ffffffff8117b88d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81185e70)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81186510-ffffffff8118651d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void touch_softlockup_watchdog_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811937c0)
Location: kernel/watchdog.c:273
Inline: True
Inline callers:
  - kernel/watchdog.c:touch_softlockup_watchdog
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_sched_handle
```
**Symbols:**

```
ffffffff81193e60-ffffffff81193e6d: touch_softlockup_watchdog_sched (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
