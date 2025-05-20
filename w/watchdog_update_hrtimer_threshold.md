# Function: <code>watchdog_update_hrtimer_threshold</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8114f690)
Location: kernel/watchdog_hld.c:45
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_thresh
```
**Symbols:**

```
ffffffff8114f690-ffffffff8114f6a5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8115bdc0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8115bdc0-ffffffff8115bdd5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8116a930)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8116a930-ffffffff8116a945: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81177940)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81177940-ffffffff81177955: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811847a0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811847a0-ffffffff811847b5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81190620)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81190620-ffffffff81190635: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a51c0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811a51c0-ffffffff811a51d5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a21b0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811a21b0-ffffffff811a21c5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a2e70)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811a2e70-ffffffff811a2e85: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811cc6a0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811cc6a0-ffffffff811cc6b5: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff812005a0)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff812005a0-ffffffff812005bb: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81248250)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81248250-ffffffff8124826b: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff8125f550)
Location: kernel/watchdog_perf.c:34
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8125f550-ffffffff8125f56b: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff81279560)
Location: kernel/watchdog_perf.c:34
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81279560-ffffffff8127957b: watchdog_update_hrtimer_threshold (STB_GLOBAL)
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:201
Inline: True
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:201
Inline: True
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:201
Inline: True
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:201
Inline: True
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
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81188c40)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81188c40-ffffffff81188c55: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8117bd80)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8117bd80-ffffffff8117bd95: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81186a10)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81186a10-ffffffff81186a25: watchdog_update_hrtimer_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void watchdog_update_hrtimer_threshold(u64 period);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81194360)
Location: kernel/watchdog_hld.c:50
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81194360-ffffffff81194375: watchdog_update_hrtimer_threshold (STB_GLOBAL)
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
