# Function: <code>perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117dc70)
Location: kernel/events/core.c:1824
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_nmi_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8117dc70-ffffffff8117dca0: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118fec0)
Location: kernel/events/core.c:1957
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_nmi_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8118fec0-ffffffff8118fef0: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fe30)
Location: kernel/events/core.c:1989
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8119fe30-ffffffff8119fe60: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7a50)
Location: kernel/events/core.c:2002
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:watchdog_nmi_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a7a50-ffffffff811a7a80: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb1c0)
Location: kernel/events/core.c:1995
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811bb1c0-ffffffff811bb1f0: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db0e0)
Location: kernel/events/core.c:2192
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
**Symbols:**

```
ffffffff811db0e0-ffffffff811db110: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb420)
Location: kernel/events/core.c:2192
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811eb420-ffffffff811eb450: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202070)
Location: kernel/events/core.c:2194
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81202070-ffffffff812020a3: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ef20)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8120ef20-ffffffff8120ef53: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81238c30)
Location: kernel/events/core.c:2426
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81238c30-ffffffff81238c63: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242bb0)
Location: kernel/events/core.c:2466
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81242bb0-ffffffff81242be3: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248010)
Location: kernel/events/core.c:2468
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81248010-ffffffff81248043: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81282370)
Location: kernel/events/core.c:2543
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81282370-ffffffff812823a3: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d22b0)
Location: kernel/events/core.c:2456
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812d22b0-ffffffff812d232b: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b120)
Location: kernel/events/core.c:2461
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8133b120-ffffffff8133b197: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c1a0)
Location: kernel/events/core.c:2461
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8136c1a0-ffffffff8136c217: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395360)
Location: kernel/events/core.c:2499
Inline: False
Direct callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81395360-ffffffff813953d7: perf_event_disable (STB_GLOBAL)
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
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010298b88)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_release_perf_event
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffff800010298b88-ffff800010298bc4: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4f6c)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c04c4f6c-c04c4fa0: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000345e90)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c000000000345e90-c000000000345ee8: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8cf0)
Location: kernel/events/core.c:2279
Inline: False
```
**Symbols:**

```
ffffffe0001c8cf0-ffffffe0001c8d34: perf_event_disable (STB_GLOBAL)
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
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207540)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81207540-ffffffff81207573: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa3e0)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811fa3e0-ffffffff811fa413: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205310)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81205310-ffffffff81205343: perf_event_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81214180)
Location: kernel/events/core.c:2279
Inline: False
Direct callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81214180-ffffffff812141b3: perf_event_disable (STB_GLOBAL)
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
