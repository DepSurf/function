# Function: <code>pci_acpi_program_hp_params</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev, const struct hotplug_program_ops *hp_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:398
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81571c54-ffffffff81571cf5: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff81571490-ffffffff8157198e: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8159320b-ffffffff815932c5: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff81592840-ffffffff81592f01: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81641290)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81641290-ffffffff8164139c: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81667780)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81667780-ffffffff8166788c: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81649bf0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81649bf0-ffffffff81649d97: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816bb6c0)
Location: drivers/pci/pci-acpi.c:746
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff816bb6c0-ffffffff816bb867: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff817df9a0)
Location: drivers/pci/pci-acpi.c:746
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff817df9a0-ffffffff817dfb5e: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81902810)
Location: drivers/pci/pci-acpi.c:747
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81902810-ffffffff819029ce: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81945ea0)
Location: drivers/pci/pci-acpi.c:747
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81945ea0-ffffffff8194605e: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198f1d0)
Location: drivers/pci/pci-acpi.c:747
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8198f1d0-ffffffff8198f38e: pci_acpi_program_hp_params (STB_GLOBAL)
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
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f8818)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffff8000106f8818-ffff8000106f8f6c: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/pci.h:660
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/pci.h:660
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/pci.h:660
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8158709b-ffffffff81587155: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff815866d0-ffffffff81586d91: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81575e4b-ffffffff81575f05: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff815754a0-ffffffff81575b61: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81586f5b-ffffffff81587015: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff81586590-ffffffff81586c51: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_acpi_program_hp_params(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff815a140b-ffffffff815a14c5: pci_acpi_program_hp_params.cold (STB_LOCAL)
ffffffff815a0a40-ffffffff815a1101: pci_acpi_program_hp_params (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct hotplug_program_ops *hp_ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
