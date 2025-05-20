# Function: <code>dpm_save_failed_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155929f)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad27c)
Location: include/linux/suspend.h:75
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dc03f)
Location: include/linux/suspend.h:75
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f0bbf)
Location: include/linux/suspend.h:75
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8165810f)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81692443)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff81690e90-ffffffff81690ed1: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2993)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff816b14f0-ffffffff816b1531: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ee02e)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171200e)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cc495)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff817ca8c0-ffffffff817ca901: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0f75)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff817df370-ffffffff817df3b1: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c5325)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff817c3760-ffffffff817c37a1: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184f708)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff8184dad0-ffffffff8184db31: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81994ed6)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
```
**Symbols:**

```
ffffffff81993250-ffffffff819932bd: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03730)
Location: include/linux/suspend.h:76
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81b03730-ffffffff81b0379d: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51720)
Location: include/linux/suspend.h:79
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81b51720-ffffffff81b517ea: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81ba9da0)
Location: include/linux/suspend.h:79
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81ba9da0-ffffffff81ba9e6a: dpm_save_failed_dev (STB_LOCAL)
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
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010901030)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffff8000108ff7d8-ffff8000108ff82c: dpm_save_failed_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dpm_save_failed_dev(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eb394)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
c09e9c70-c09e9cb8: dpm_save_failed_dev (STB_LOCAL)
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
In drivers/base/power/main.c (c0000000009a0e78)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d838e)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b29ee)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81705cce)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81720679)
Location: include/linux/suspend.h:76
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
