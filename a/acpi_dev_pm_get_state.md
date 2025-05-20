# Function: <code>acpi_dev_pm_get_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147ca41)
Location: drivers/acpi/device_pm.c:515
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff8147ca41-ffffffff8147cbf2: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb1c0)
Location: drivers/acpi/device_pm.c:517
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff814cb1c0-ffffffff814cb371: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed0ec)
Location: drivers/acpi/device_pm.c:517
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff814ed0ec-ffffffff814ed29d: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814f9b30)
Location: drivers/acpi/device_pm.c:529
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff814f9b30-ffffffff814f9ced: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153b300)
Location: drivers/acpi/device_pm.c:538
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff8153b300-ffffffff8153b4d6: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81571160)
Location: drivers/acpi/device_pm.c:538
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff81571160-ffffffff81571336: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81588d30)
Location: drivers/acpi/device_pm.c:539
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff81588d30-ffffffff81588f06: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b99f0)
Location: drivers/acpi/device_pm.c:580
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815b99f0-ffffffff815b9bcf: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dac30)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815dac30-ffffffff815dae0f: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685220)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff81685220-ffffffff816853f5: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a2fd0)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff816a2fd0-ffffffff816a31a5: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685dc0)
Location: drivers/acpi/device_pm.c:582
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff81685dc0-ffffffff81685f98: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fb0c0)
Location: drivers/acpi/device_pm.c:582
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff816fb0c0-ffffffff816fb298: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81828550)
Location: drivers/acpi/device_pm.c:608
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff81828550-ffffffff81828737: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195a5c0)
Location: drivers/acpi/device_pm.c:655
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff8195a5c0-ffffffff8195a7c0: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a0a20)
Location: drivers/acpi/device_pm.c:655
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff819a0a20-ffffffff819a0c85: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e9090)
Location: drivers/acpi/device_pm.c:668
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff819e9090-ffffffff819e92f5: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010768160)
Location: drivers/acpi/device_pm.c:585
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffff800010768160-ffff800010768240: acpi_dev_pm_get_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cd400)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815cd400-ffffffff815cd5df: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b6f80)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815b6f80-ffffffff815b715f: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cef10)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815cef10-ffffffff815cf0ef: acpi_dev_pm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_dev_pm_get_state(struct device *dev, struct acpi_device *adev, u32 target_state, int *d_min_p, int *d_max_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e8dd0)
Location: drivers/acpi/device_pm.c:585
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
**Symbols:**

```
ffffffff815e8dd0-ffffffff815e8faf: acpi_dev_pm_get_state (STB_LOCAL)
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
