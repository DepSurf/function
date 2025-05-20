# Function: <code>dpm_run_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81558910)
Location: drivers/base/power/main.c:376
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff81558910-ffffffff81558a41: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aaa70)
Location: drivers/base/power/main.c:378
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff815aaa70-ffffffff815aab8b: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d9850)
Location: drivers/base/power/main.c:436
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff815d9850-ffffffff815d998e: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ee240)
Location: drivers/base/power/main.c:444
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff815ee240-ffffffff815ee37f: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816556a0)
Location: drivers/base/power/main.c:441
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816556a0-ffffffff816557ea: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:437
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81691160-ffffffff816912af: dpm_run_callback (STB_LOCAL)
ffffffff81694400-ffffffff8169441e: dpm_run_callback.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:438
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816b1750-ffffffff816b189f: dpm_run_callback (STB_LOCAL)
ffffffff816b4a80-ffffffff816b4a9e: dpm_run_callback.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:445
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816eb570-ffffffff816eb6b1: dpm_run_callback (STB_LOCAL)
ffffffff816ee962-ffffffff816ee994: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8170f630-ffffffff8170f771: dpm_run_callback (STB_LOCAL)
ffffffff81712942-ffffffff81712974: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:477
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff817cab30-ffffffff817cac5e: dpm_run_callback (STB_LOCAL)
ffffffff817ce189-ffffffff817ce1bb: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:476
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff817df5e0-ffffffff817df6e8: dpm_run_callback (STB_LOCAL)
ffffffff81c0ed5d-ffffffff81c0ed8e: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:477
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff817c39c0-ffffffff817c3ac8: dpm_run_callback (STB_LOCAL)
ffffffff81c00ed6-ffffffff81c00f07: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:474
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8184dd60-ffffffff8184de7d: dpm_run_callback (STB_LOCAL)
ffffffff81d03990-ffffffff81d039f9: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81993600-ffffffff8199375f: dpm_run_callback (STB_LOCAL)
ffffffff81ecc258-ffffffff81ecc2ae: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81b03d90-ffffffff81b03f33: dpm_run_callback (STB_LOCAL)
ffffffff820988e7-ffffffff820988fc: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81b52130-ffffffff81b522d3: dpm_run_callback (STB_LOCAL)
ffffffff821198f8-ffffffff8211990d: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81baa720-ffffffff81baa8c3: dpm_run_callback (STB_LOCAL)
ffffffff821f78ba-ffffffff821f78cf: dpm_run_callback.cold (STB_LOCAL)
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
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ffc68)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffff8000108ffc68-ffff8000108ffe50: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e9f08)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c09e9f08-c09ea114: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099d130)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c00000000099d130-c00000000099d394: dpm_run_callback (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816d5370-ffffffff816d54b1: dpm_run_callback (STB_LOCAL)
ffffffff816d8cc2-ffffffff816d8cf4: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816b0020-ffffffff816b0161: dpm_run_callback (STB_LOCAL)
ffffffff816b3302-ffffffff816b3334: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff817032f0-ffffffff81703431: dpm_run_callback (STB_LOCAL)
ffffffff81706602-ffffffff81706634: dpm_run_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dpm_run_callback(pm_callback_t cb, struct device *dev, pm_message_t state, const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8171db10-ffffffff8171dc8a: dpm_run_callback (STB_LOCAL)
ffffffff81721012-ffffffff81721044: dpm_run_callback.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *info</code> ➡️ <code>const char *info</code>
</li>
</ul>
</details>
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
