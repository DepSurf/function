# Function: <code>acpi_dev_power_up_children_with_adr</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_dev_power_up_children_with_adr(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8182a040)
Location: drivers/acpi/device_pm.c:454
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8182a040-ffffffff8182a065: acpi_dev_power_up_children_with_adr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_dev_power_up_children_with_adr(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195c4a0)
Location: drivers/acpi/device_pm.c:482
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff8195c4a0-ffffffff8195c4c5: acpi_dev_power_up_children_with_adr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_dev_power_up_children_with_adr(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a2990)
Location: drivers/acpi/device_pm.c:482
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff819a2990-ffffffff819a29b5: acpi_dev_power_up_children_with_adr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_dev_power_up_children_with_adr(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819eb040)
Location: drivers/acpi/device_pm.c:495
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
**Symbols:**

```
ffffffff819eb040-ffffffff819eb065: acpi_dev_power_up_children_with_adr (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
