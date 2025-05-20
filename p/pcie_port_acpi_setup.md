# Function: <code>pcie_port_acpi_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcie_port_acpi_setup(struct pci_dev *port, int *srv_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81449420)
Location: drivers/pci/pcie/portdrv_acpi.c:35
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81449420-ffffffff814494c8: pcie_port_acpi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcie_port_acpi_setup(struct pci_dev *port, int *srv_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495720)
Location: drivers/pci/pcie/portdrv_acpi.c:35
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81495720-ffffffff814957b2: pcie_port_acpi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcie_port_acpi_setup(struct pci_dev *port, int *srv_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b70e0)
Location: drivers/pci/pcie/portdrv_acpi.c:35
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff814b70e0-ffffffff814b7172: pcie_port_acpi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_port_acpi_setup(struct pci_dev *port, int *srv_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a20)
Location: drivers/pci/pcie/portdrv_acpi.c:35
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff814c1a20-ffffffff814c1ab3: pcie_port_acpi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_port_acpi_setup(struct pci_dev *port, int *srv_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81501c30)
Location: drivers/pci/pcie/portdrv_acpi.c:35
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81501c30-ffffffff81501cc6: pcie_port_acpi_setup (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
</ul>
