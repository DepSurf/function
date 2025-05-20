# Function: <code>acpi_device_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_wakeup(struct acpi_device *adev, u32 target_state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d061)
Location: drivers/acpi/device_pm.c:685
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
```
**Symbols:**

```
ffffffff8147d061-ffffffff8147d0ed: acpi_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_wakeup(struct acpi_device *adev, u32 target_state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb817)
Location: drivers/acpi/device_pm.c:687
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
```
**Symbols:**

```
ffffffff814cb817-ffffffff814cb8a3: acpi_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_wakeup(struct acpi_device *adev, u32 target_state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed745)
Location: drivers/acpi/device_pm.c:687
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
```
**Symbols:**

```
ffffffff814ed745-ffffffff814ed7d1: acpi_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_wakeup(struct acpi_device *adev, u32 target_state, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fa410)
Location: drivers/acpi/device_pm.c:698
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff814fa410-ffffffff814fa4a4: acpi_device_wakeup (STB_LOCAL)
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
