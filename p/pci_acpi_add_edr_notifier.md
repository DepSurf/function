# Function: <code>pci_acpi_add_edr_notifier</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci-acpi.h:121
Inline: True
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
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci-acpi.h:121
Inline: True
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
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci-acpi.h:121
Inline: True
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
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci-acpi.h:121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_acpi_add_edr_notifier(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/edr.c (0)
Location: drivers/pci/pcie/edr.c:205
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81ead852-ffffffff81ead8d1: pci_acpi_add_edr_notifier.cold (STB_LOCAL)
ffffffff817dd4f0-ffffffff817dd695: pci_acpi_add_edr_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_acpi_add_edr_notifier(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/edr.c (ffffffff818ffed0)
Location: drivers/pci/pcie/edr.c:205
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff818ffed0-ffffffff819000f2: pci_acpi_add_edr_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_acpi_add_edr_notifier(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/edr.c (ffffffff81943450)
Location: drivers/pci/pcie/edr.c:215
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81943450-ffffffff81943672: pci_acpi_add_edr_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_acpi_add_edr_notifier(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/edr.c (ffffffff8198c720)
Location: drivers/pci/pcie/edr.c:215
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff8198c720-ffffffff8198c942: pci_acpi_add_edr_notifier (STB_GLOBAL)
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
