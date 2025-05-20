# Function: <code>__acpi_device_wakeup_enable</code>

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
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153b8e0)
Location: drivers/acpi/device_pm.c:704
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff8153b8e0-ffffffff8153b97b: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81571720)
Location: drivers/acpi/device_pm.c:704
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81571720-ffffffff815717bb: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815894f0)
Location: drivers/acpi/device_pm.c:705
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815894f0-ffffffff8158958b: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b9ff0)
Location: drivers/acpi/device_pm.c:746
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815b9ff0-ffffffff815ba0c7: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db230)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815db230-ffffffff815db307: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816857b0)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff816857b0-ffffffff81685887: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3560)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff816a3560-ffffffff816a3695: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686360)
Location: drivers/acpi/device_pm.c:748
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81686360-ffffffff81686495: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fb670)
Location: drivers/acpi/device_pm.c:748
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff816fb670-ffffffff816fb7a2: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81828b50)
Location: drivers/acpi/device_pm.c:774
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81828b50-ffffffff81828c70: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195ac50)
Location: drivers/acpi/device_pm.c:836
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff8195ac50-ffffffff8195ad6d: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a1120)
Location: drivers/acpi/device_pm.c:836
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff819a1120-ffffffff819a123d: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e97d0)
Location: drivers/acpi/device_pm.c:849
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff819e97d0-ffffffff819e98ed: __acpi_device_wakeup_enable (STB_LOCAL)
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
In drivers/acpi/device_pm.c (ffff800010767f00)
Location: drivers/acpi/device_pm.c:751
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffff800010767f00-ffff800010767fb0: __acpi_device_wakeup_enable.constprop.0 (STB_LOCAL)
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
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cda00)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cda00-ffffffff815cdad7: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7580)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815b7580-ffffffff815b7657: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cf510)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cf510-ffffffff815cf5e7: __acpi_device_wakeup_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device *adev, u32 target_state, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e93d0)
Location: drivers/acpi/device_pm.c:751
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815e93d0-ffffffff815e94a7: __acpi_device_wakeup_enable (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int max_count</code>
</li>
</ul>
</details>
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
