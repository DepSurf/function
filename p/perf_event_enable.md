# Function: <code>perf_event_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117dad0)
Location: kernel/events/core.c:2359
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8117dad0-ffffffff8117db00: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ff70)
Location: kernel/events/core.c:2453
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8118ff70-ffffffff8118ffa0: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fee0)
Location: kernel/events/core.c:2517
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8119fee0-ffffffff8119ff10: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7b00)
Location: kernel/events/core.c:2600
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a7b00-ffffffff811a7b30: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb270)
Location: kernel/events/core.c:2512
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811bb270-ffffffff811bb2a0: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db190)
Location: kernel/events/core.c:2721
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
```
**Symbols:**

```
ffffffff811db190-ffffffff811db1c0: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb4d0)
Location: kernel/events/core.c:2721
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811eb4d0-ffffffff811eb500: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812020b0)
Location: kernel/events/core.c:2739
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812020b0-ffffffff812020e3: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ef60)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8120ef60-ffffffff8120ef93: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81238d60)
Location: kernel/events/core.c:2993
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81238d60-ffffffff81238d93: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242d00)
Location: kernel/events/core.c:3037
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81242d00-ffffffff81242d33: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248160)
Location: kernel/events/core.c:3039
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81248160-ffffffff81248193: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812824c0)
Location: kernel/events/core.c:3081
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812824c0-ffffffff812824f3: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d21c0)
Location: kernel/events/core.c:2992
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812d21c0-ffffffff812d21fd: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b010)
Location: kernel/events/core.c:2993
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8133b010-ffffffff8133b04d: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c090)
Location: kernel/events/core.c:2993
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:watchdog_hardlockup_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8136c090-ffffffff8136c0cd: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395250)
Location: kernel/events/core.c:3031
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:watchdog_hardlockup_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81395250-ffffffff8139528d: perf_event_enable (STB_GLOBAL)
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
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010296d78)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffff800010296d78-ffff800010296db4: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4f38)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c04c4f38-c04c4f6c: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000346020)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c000000000346020-c000000000346078: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8e22)
Location: kernel/events/core.c:2824
Inline: False
```
**Symbols:**

```
ffffffe0001c8e22-ffffffe0001c8e66: perf_event_enable (STB_GLOBAL)
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
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207580)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81207580-ffffffff812075b3: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa420)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811fa420-ffffffff811fa453: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205350)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81205350-ffffffff81205383: perf_event_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812141c0)
Location: kernel/events/core.c:2824
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_enable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812141c0-ffffffff812141f3: perf_event_enable (STB_GLOBAL)
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
