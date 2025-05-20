# Function: <code>pcie_aer_get_firmware_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff8144b4a0)
Location: drivers/pci/pcie/aer/aerdrv_acpi.c:111
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
```
**Symbols:**

```
ffffffff8144b4a0-ffffffff8144b561: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff81497720)
Location: drivers/pci/pcie/aer/aerdrv_acpi.c:111
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
**Symbols:**

```
ffffffff81497720-ffffffff814977e1: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814b9080)
Location: drivers/pci/pcie/aer/aerdrv_acpi.c:111
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
**Symbols:**

```
ffffffff814b9080-ffffffff814b9141: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff814c3880)
Location: drivers/pci/pcie/aer/aerdrv_acpi.c:111
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
```
**Symbols:**

```
ffffffff814c3880-ffffffff814c393d: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_acpi.c (ffffffff81503ac0)
Location: drivers/pci/pcie/aer/aerdrv_acpi.c:112
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81503ac0-ffffffff81503b7d: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815338e5)
Location: drivers/pci/pcie/aer.c:301
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81534640-ffffffff8153467a: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154b40e)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8154acb0-ffffffff8154ad4a: pcie_aer_get_firmware_first.part.17 (STB_LOCAL)
ffffffff8154b200-ffffffff8154b222: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b28c)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8157ab80-ffffffff8157ac16: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffffffff8157b090-ffffffff8157b0b2: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159ccec)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8159c5c0-ffffffff8159c656: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffffffff8159caf0-ffffffff8159cb12: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010704be4)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffff800010704228-ffff8000107042d0: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffff800010704988-ffff8000107049dc: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c034)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/dpc.c (c089d8ec)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d2e76)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/dpc.c (ffffffe0004d44d8)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590856)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/dpc.c (ffffffff81591c00)
Location: drivers/pci/pcie/portdrv.h:156
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157f6bc)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff8157ef90-ffffffff8157f026: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffffffff8157f4c0-ffffffff8157f4e2: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590a3c)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff81590310-ffffffff815903a6: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffffffff81590840-ffffffff81590862: pcie_aer_get_firmware_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_aer_get_firmware_first(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815aaeec)
Location: drivers/pci/pcie/aer.c:306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
Direct callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_uncorrect_error_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:dpc_probe
```
**Symbols:**

```
ffffffff815aa7c0-ffffffff815aa856: pcie_aer_get_firmware_first.part.0 (STB_LOCAL)
ffffffff815aacf0-ffffffff815aad12: pcie_aer_get_firmware_first (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
