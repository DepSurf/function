# Function: <code>acpi_dev_pm_full_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_full_power(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d1b7)
Location: drivers/acpi/device_pm.c:791
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
```
**Symbols:**

```
ffffffff8147d1b7-ffffffff8147d1d2: acpi_dev_pm_full_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_full_power(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb965)
Location: drivers/acpi/device_pm.c:793
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
```
**Symbols:**

```
ffffffff814cb965-ffffffff814cb980: acpi_dev_pm_full_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_pm_full_power(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed893)
Location: drivers/acpi/device_pm.c:793
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
```
**Symbols:**

```
ffffffff814ed893-ffffffff814ed8ae: acpi_dev_pm_full_power (STB_LOCAL)
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
In drivers/acpi/device_pm.c (ffffffff814fa90d)
Location: drivers/acpi/device_pm.c:777
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
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
In drivers/acpi/device_pm.c (ffffffff8153c55e)
Location: drivers/acpi/device_pm.c:855
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81572407)
Location: drivers/acpi/device_pm.c:855
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8158a1e7)
Location: drivers/acpi/device_pm.c:856
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff815bacc7)
Location: drivers/acpi/device_pm.c:900
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff815dbf95)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff81686b25)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff816a48d5)
Location: drivers/acpi/device_pm.c:901
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff81687655)
Location: drivers/acpi/device_pm.c:898
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff816fcad5)
Location: drivers/acpi/device_pm.c:898
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff8182a209)
Location: drivers/acpi/device_pm.c:924
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff8195c709)
Location: drivers/acpi/device_pm.c:986
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff819a2bf9)
Location: drivers/acpi/device_pm.c:986
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff819eb2a9)
Location: drivers/acpi/device_pm.c:999
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffff800010767eb8)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce665)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff815b8225)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff815d0275)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
In drivers/acpi/device_pm.c (ffffffff815ea135)
Location: drivers/acpi/device_pm.c:905
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume
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
</ul>
