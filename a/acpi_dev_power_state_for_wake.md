# Function: <code>acpi_dev_power_state_for_wake</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 acpi_dev_power_state_for_wake(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195c4e0)
Location: drivers/acpi/device_pm.c:494
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
```
**Symbols:**

```
ffffffff8195c4e0-ffffffff8195c54b: acpi_dev_power_state_for_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 acpi_dev_power_state_for_wake(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a29d0)
Location: drivers/acpi/device_pm.c:494
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
```
**Symbols:**

```
ffffffff819a29d0-ffffffff819a2a3b: acpi_dev_power_state_for_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 acpi_dev_power_state_for_wake(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819eb080)
Location: drivers/acpi/device_pm.c:507
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
```
**Symbols:**

```
ffffffff819eb080-ffffffff819eb0eb: acpi_dev_power_state_for_wake (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
