# Function: <code>acpi_get_hp_hw_control_from_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e880)
Location: drivers/pci/hotplug/acpi_pcihp.c:84
Inline: False
```
**Symbols:**

```
ffffffff8144e880-ffffffff8144ec56: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b030)
Location: drivers/pci/hotplug/acpi_pcihp.c:84
Inline: False
```
**Symbols:**

```
ffffffff8149b030-ffffffff8149b444: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bcc10)
Location: drivers/pci/hotplug/acpi_pcihp.c:84
Inline: False
```
**Symbols:**

```
ffffffff814bcc10-ffffffff814bd024: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c73e0)
Location: drivers/pci/hotplug/acpi_pcihp.c:84
Inline: False
```
**Symbols:**

```
ffffffff814c73e0-ffffffff814c780b: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815079a0)
Location: drivers/pci/hotplug/acpi_pcihp.c:84
Inline: False
```
**Symbols:**

```
ffffffff815079a0-ffffffff81507da5: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81538df3-ffffffff81538e3d: acpi_get_hp_hw_control_from_firmware.cold.2 (STB_LOCAL)
ffffffff815389a0-ffffffff81538c16: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff81550183-ffffffff815501cd: acpi_get_hp_hw_control_from_firmware.cold.2 (STB_LOCAL)
ffffffff8154fd00-ffffffff8154ffa2: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff8157ffd3-ffffffff8158003f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff8157fbc0-ffffffff8157fde1: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff815a1a13-ffffffff815a1a7f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff815a1600-ffffffff815a1821: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8164a496-ffffffff8164a4db: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff8164a080-ffffffff8164a1ed: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81bfbc2a-ffffffff81bfbc6f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff8166e970-ffffffff8166eadd: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81beda6c-ffffffff81bedad8: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff81650df0-ffffffff81651011: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81ce8796-ffffffff81ce8810: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff816c2ba0-ffffffff816c2dca: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81eaf812-ffffffff81eaf8c6: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff817e8670-ffffffff817e888d: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8208f803-ffffffff8208f818: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff8190def0-ffffffff8190e216: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8210fb64-ffffffff8210fb78: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff81951570-ffffffff81951893: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff821ed88c-ffffffff821ed8a0: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff8199a9d0-ffffffff8199acf3: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
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
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (ffff800010709d30)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffff800010709d30-ffff800010709f98: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
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
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/linux/pci_hotplug.h:97
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
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff81595223-ffffffff8159528f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff81594e10-ffffffff81595031: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff815843b3-ffffffff8158441f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff81583fa0-ffffffff815841c1: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff81595763-ffffffff815957cf: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff81595350-ffffffff81595571: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_get_hp_hw_control_from_firmware(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpi_pcihp.c (0)
Location: drivers/pci/hotplug/acpi_pcihp.c:68
Inline: False
```
**Symbols:**

```
ffffffff815afbe3-ffffffff815afc4f: acpi_get_hp_hw_control_from_firmware.cold (STB_LOCAL)
ffffffff815af7d0-ffffffff815af9f1: acpi_get_hp_hw_control_from_firmware (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
