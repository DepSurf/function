# Function: <code>pci_get_hp_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814578d0)
Location: drivers/pci/pci-acpi.c:256
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff814578d0-ffffffff81457e24: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814a4510)
Location: drivers/pci/pci-acpi.c:256
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff814a4510-ffffffff814a4a4c: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814c6320)
Location: drivers/pci/pci-acpi.c:332
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff814c6320-ffffffff814c685c: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814d01e0)
Location: drivers/pci/pci-acpi.c:331
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff814d01e0-ffffffff814d06cb: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81510420)
Location: drivers/pci/pci-acpi.c:331
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81510420-ffffffff81510902: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:331
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81545ee6-ffffffff81545f49: pci_get_hp_params.cold.7 (STB_LOCAL)
ffffffff81545560-ffffffff815459dd: pci_get_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pci_get_hp_params(struct pci_dev *dev, struct hotplug_params *hpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:331
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff815420e6-ffffffff81542149: pci_get_hp_params.cold.10 (STB_LOCAL)
ffffffff815415a0-ffffffff81541a29: pci_get_hp_params (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
