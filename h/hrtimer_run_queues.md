# Function: <code>hrtimer_run_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810efcf0)
Location: kernel/time/hrtimer.c:1432
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810efcf0-ffffffff810efdb8: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f6b30)
Location: kernel/time/hrtimer.c:1422
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810f6b30-ffffffff810f6bf8: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fdbe0)
Location: kernel/time/hrtimer.c:1422
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810fdbe0-ffffffff810fdca8: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ffe50)
Location: kernel/time/hrtimer.c:1394
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810ffe50-ffffffff810fff18: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110ac40)
Location: kernel/time/hrtimer.c:1399
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8110ac40-ffffffff8110ad08: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1602
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff81116e2e-ffffffff81116e44: hrtimer_run_queues.cold.27 (STB_LOCAL)
ffffffff811165e0-ffffffff811166fd: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1592
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8112246e-ffffffff81122484: hrtimer_run_queues.cold.29 (STB_LOCAL)
ffffffff81121c20-ffffffff81121d3d: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1592
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8112cda5-ffffffff8112cdb9: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff8112c550-ffffffff8112c683: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff81138d72-ffffffff81138d86: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81138570-ffffffff811386a3: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1729
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81147cd2-ffffffff81147ce6: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81147380-ffffffff811474b3: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1746
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81be3852-ffffffff81be3866: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81143890-ffffffff811439c3: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1746
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81bd56d4-ffffffff81bd56e8: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81144a40-ffffffff81144b73: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1894
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81cb09f5-ffffffff81cb0a1e: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81168290-ffffffff811683cf: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1894
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81e61f8c-ffffffff81e61fb6: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff8119bc90-ffffffff8119bde6: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1894
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8205ae3d-ffffffff8205ae52: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff811da5d0-ffffffff811da737: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1897
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff820d96f1-ffffffff820d9706: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff811eeb00-ffffffff811eec67: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1898
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff821b4ff0-ffffffff821b5005: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81204c80-ffffffff81204de7: hrtimer_run_queues (STB_GLOBAL)
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
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a2190)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffff8000101a2190-ffff8000101a2328: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ebef0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
c03ebef0-c03ec044: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000203630)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
c000000000203630-c0000000002037e8: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f33e)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffe00012f33e-ffffffe00012f486: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff81131522-ffffffff81131536: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81130d20-ffffffff81130e53: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff81123f86-ffffffff81123f9a: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff81123790-ffffffff811238c3: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8112f242-ffffffff8112f256: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff8112ea40-ffffffff8112eb73: hrtimer_run_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hrtimer_run_queues();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:1724
Inline: False
Direct callers:
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8113bc5d-ffffffff8113bc71: hrtimer_run_queues.cold (STB_LOCAL)
ffffffff8113b440-ffffffff8113b573: hrtimer_run_queues (STB_GLOBAL)
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
