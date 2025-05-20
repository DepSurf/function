# Function: <code>acpi_pm_device_run_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_device_run_wake(struct device *phys_dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d0ed)
Location: drivers/acpi/device_pm.c:723
Inline: True
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
```
**Symbols:**

```
ffffffff8147d0ed-ffffffff8147d164: acpi_pm_device_run_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_device_run_wake(struct device *phys_dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cb8a3)
Location: drivers/acpi/device_pm.c:725
Inline: True
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff814cb8a3-ffffffff814cb912: acpi_pm_device_run_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_device_run_wake(struct device *phys_dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ed7d1)
Location: drivers/acpi/device_pm.c:725
Inline: True
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff814ed7d1-ffffffff814ed840: acpi_pm_device_run_wake (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
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
</ul>
