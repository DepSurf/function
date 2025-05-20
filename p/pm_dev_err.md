# Function: <code>pm_dev_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81558620)
Location: drivers/base/power/main.c:352
Inline: False
Direct callers:
  - drivers/base/power/main.c:async_resume_noirq
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:async_resume
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
**Symbols:**

```
ffffffff81558620-ffffffff81558669: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aa720)
Location: drivers/base/power/main.c:354
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815aa720-ffffffff815aa769: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d9450)
Location: drivers/base/power/main.c:412
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815d9450-ffffffff815d9499: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815edf10)
Location: drivers/base/power/main.c:414
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815edf10-ffffffff815edf57: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816552c0)
Location: drivers/base/power/main.c:414
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816552c0-ffffffff81655307: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816943a0)
Location: drivers/base/power/main.c:410
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816943a0-ffffffff816943e7: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b4a20)
Location: drivers/base/power/main.c:411
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816b4a20-ffffffff816b4a67: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:418
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816eb250-ffffffff816eb280: pm_dev_err (STB_LOCAL)
ffffffff816ee8e0-ffffffff816ee8ff: pm_dev_err.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff8170f210-ffffffff8170f240: pm_dev_err (STB_LOCAL)
ffffffff817128c0-ffffffff817128df: pm_dev_err.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817ce0e0)
Location: drivers/base/power/main.c:450
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff817ce0e0-ffffffff817ce126: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81c0ecb4)
Location: drivers/base/power/main.c:449
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81c0ecb4-ffffffff81c0ecfa: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81c00e36)
Location: drivers/base/power/main.c:450
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81c00e36-ffffffff81c00e72: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81d038f0)
Location: drivers/base/power/main.c:447
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81d038f0-ffffffff81d0392c: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81ecc0c1)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81ecc0c1-ffffffff81ecc10f: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b07268)
Location: drivers/base/power/main.c:446
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b552b8)
Location: drivers/base/power/main.c:446
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bad878)
Location: drivers/base/power/main.c:446
Inline: True
Inline callers:
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
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff80001090356c)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffff80001090356c-ffff8000109035dc: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ed884)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
c09ed884-c09ed8e0: pm_dev_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099ca70)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
c00000000099ca70-c00000000099caf0: pm_dev_err (STB_LOCAL)
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
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816d4f50-ffffffff816d4f80: pm_dev_err (STB_LOCAL)
ffffffff816d8c40-ffffffff816d8c5f: pm_dev_err.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816afc00-ffffffff816afc30: pm_dev_err (STB_LOCAL)
ffffffff816b3280-ffffffff816b329f: pm_dev_err.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81702ed0-ffffffff81702f00: pm_dev_err (STB_LOCAL)
ffffffff81706580-ffffffff8170659f: pm_dev_err.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pm_dev_err(struct device *dev, pm_message_t state, const char *info, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:446
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:async_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:async_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff8171d750-ffffffff8171d780: pm_dev_err (STB_LOCAL)
ffffffff81720f90-ffffffff81720faf: pm_dev_err.cold (STB_LOCAL)
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
