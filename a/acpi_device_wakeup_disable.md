# Function: <code>acpi_device_wakeup_disable</code>

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
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153b880)
Location: drivers/acpi/device_pm.c:764
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff8153b880-ffffffff8153b8d3: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815716c0)
Location: drivers/acpi/device_pm.c:764
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815716c0-ffffffff81571713: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589490)
Location: drivers/acpi/device_pm.c:765
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81589490-ffffffff815894e3: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b9f90)
Location: drivers/acpi/device_pm.c:809
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815b9f90-ffffffff815b9fe3: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db1d0)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815db1d0-ffffffff815db223: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686b2d)
Location: drivers/acpi/device_pm.c:814
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a48e0)
Location: drivers/acpi/device_pm.c:828
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81687660)
Location: drivers/acpi/device_pm.c:825
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fcae0)
Location: drivers/acpi/device_pm.c:825
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8182a214)
Location: drivers/acpi/device_pm.c:851
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
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
In drivers/acpi/device_pm.c (ffffffff8195c711)
Location: drivers/acpi/device_pm.c:913
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
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
In drivers/acpi/device_pm.c (ffffffff819a2c01)
Location: drivers/acpi/device_pm.c:913
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
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
In drivers/acpi/device_pm.c (ffffffff819eb2b1)
Location: drivers/acpi/device_pm.c:926
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
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
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767440)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffff800010767440-ffff8000107674a0: acpi_device_wakeup_disable (STB_LOCAL)
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
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cd9a0)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cd9a0-ffffffff815cd9f3: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7520)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815b7520-ffffffff815b7573: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cf4b0)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cf4b0-ffffffff815cf503: acpi_device_wakeup_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_device_wakeup_disable(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9370)
Location: drivers/acpi/device_pm.c:814
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815e9370-ffffffff815e93c3: acpi_device_wakeup_disable (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
