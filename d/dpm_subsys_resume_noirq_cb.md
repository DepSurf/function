# Function: <code>dpm_subsys_resume_noirq_cb</code>

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
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81690a90)
Location: drivers/base/power/main.c:569
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81690a90-ffffffff81690b36: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b10f0)
Location: drivers/base/power/main.c:570
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816b10f0-ffffffff816b1196: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eada0)
Location: drivers/base/power/main.c:562
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816eada0-ffffffff816eae43: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170ede0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8170ede0-ffffffff8170ee83: dpm_subsys_resume_noirq_cb (STB_LOCAL)
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
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ff1b8)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffff8000108ff1b8-ffff8000108ff318: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e97c8)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c09e97c8-c09e988c: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099c110)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
c00000000099c110-c00000000099c2c8: dpm_subsys_resume_noirq_cb (STB_LOCAL)
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
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d4400)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816d4400-ffffffff816d4685: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816af7d0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816af7d0-ffffffff816af873: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81702aa0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81702aa0-ffffffff81702b43: dpm_subsys_resume_noirq_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pm_callback_t dpm_subsys_resume_noirq_cb(struct device *dev, pm_message_t state, const char **info_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171d2c0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff8171d2c0-ffffffff8171d363: dpm_subsys_resume_noirq_cb (STB_LOCAL)
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
