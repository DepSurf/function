# Function: <code>dpm_subsys_suspend_late_cb</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81690bf0)
Location: drivers/base/power/main.c:1462
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81690bf0-ffffffff81690c96: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1250)
Location: drivers/base/power/main.c:1464
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816b1250-ffffffff816b12f6: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eafb0)
Location: drivers/base/power/main.c:1452
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816eafb0-ffffffff816eb053: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170eff0)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8170eff0-ffffffff8170f093: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ff478)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffff8000108ff478-ffff8000108ff5d8: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e99bc)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c09e99bc-c09e9a80: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099c650)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c00000000099c650-c00000000099c808: dpm_subsys_suspend_late_cb (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d4b80)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816d4b80-ffffffff816d4dd5: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816af9e0)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816af9e0-ffffffff816afa83: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81702cb0)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81702cb0-ffffffff81702d53: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_suspend_late_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171d530)
Location: drivers/base/power/main.c:1473
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8171d530-ffffffff8171d5d3: dpm_subsys_suspend_late_cb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
