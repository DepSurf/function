# Function: <code>acpi_dev_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_dev_runtime_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d1d2)
Location: drivers/acpi/device_pm.c:837
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
```
**Symbols:**

```
ffffffff8147d1d2-ffffffff8147d211: acpi_dev_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_dev_runtime_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb980)
Location: drivers/acpi/device_pm.c:839
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
**Symbols:**

```
ffffffff814cb980-ffffffff814cb9c2: acpi_dev_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_dev_runtime_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed8ae)
Location: drivers/acpi/device_pm.c:839
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
**Symbols:**

```
ffffffff814ed8ae-ffffffff814ed8f0: acpi_dev_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_dev_runtime_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fa960)
Location: drivers/acpi/device_pm.c:823
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
**Symbols:**

```
ffffffff814fa960-ffffffff814fa9c7: acpi_dev_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
