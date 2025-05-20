# Function: <code>hardlockup_detector_perf_cleanup</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8115be70)
Location: kernel/watchdog_hld.c:222
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8115be70-ffffffff8115bf0d: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:222
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8116ab0f-ffffffff8116ab1b: hardlockup_detector_perf_cleanup.cold.9 (STB_LOCAL)
ffffffff8116a9e0-ffffffff8116aa75: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:222
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81177b06-ffffffff81177b12: hardlockup_detector_perf_cleanup.cold.9 (STB_LOCAL)
ffffffff811779f0-ffffffff81177a85: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8118496c-ffffffff81184978: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff81184850-ffffffff811848eb: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811907ec-ffffffff811907f8: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff811906d0-ffffffff8119076b: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811a5397-ffffffff811a53a3: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff811a5280-ffffffff811a5313: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81be5075-ffffffff81be5081: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff811a2270-ffffffff811a2303: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81bd6e65-ffffffff81bd6e71: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff811a2f30-ffffffff811a2fc3: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81cb3f73-ffffffff81cb3f7f: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff811cc760-ffffffff811cc82d: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81e64e21-ffffffff81e64e2d: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff81200670-ffffffff81200749: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81248360)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81248360-ffffffff8124844d: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff8125f680)
Location: kernel/watchdog_perf.c:178
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8125f680-ffffffff8125f76d: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff81279690)
Location: kernel/watchdog_perf.c:178
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81279690-ffffffff8127977d: hardlockup_detector_perf_cleanup (STB_GLOBAL)
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
Location: include/linux/nmi.h:110
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
Location: include/linux/nmi.h:110
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
Location: include/linux/nmi.h:110
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
Location: include/linux/nmi.h:110
Inline: True
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
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81188e0c-ffffffff81188e18: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff81188cf0-ffffffff81188d8b: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8117bf4c-ffffffff8117bf58: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff8117be30-ffffffff8117becb: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81186bdc-ffffffff81186be8: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff81186ac0-ffffffff81186b5b: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hardlockup_detector_perf_cleanup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:223
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_cleanup
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8119452c-ffffffff81194538: hardlockup_detector_perf_cleanup.cold (STB_LOCAL)
ffffffff81194410-ffffffff811944ab: hardlockup_detector_perf_cleanup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
