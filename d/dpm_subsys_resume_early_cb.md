# Function: <code>dpm_subsys_resume_early_cb</code>

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
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81690b40)
Location: drivers/base/power/main.c:780
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff81690b40-ffffffff81690be6: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b11a0)
Location: drivers/base/power/main.c:781
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff816b11a0-ffffffff816b1246: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eae50)
Location: drivers/base/power/main.c:783
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff816eae50-ffffffff816eaef3: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170ee90)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff8170ee90-ffffffff8170ef33: dpm_subsys_resume_early_cb (STB_LOCAL)
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
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ff318)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffff8000108ff318-ffff8000108ff478: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e988c)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
c09e988c-c09e9950: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099c2d0)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
c00000000099c2d0-c00000000099c488: dpm_subsys_resume_early_cb (STB_LOCAL)
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
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d4690)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff816d4690-ffffffff816d48e5: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816af880)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff816af880-ffffffff816af923: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81702b50)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff81702b50-ffffffff81702bf3: dpm_subsys_resume_early_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_early_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171d370)
Location: drivers/base/power/main.c:809
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_early
```
**Symbols:**

```
ffffffff8171d370-ffffffff8171d413: dpm_subsys_resume_early_cb (STB_LOCAL)
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
