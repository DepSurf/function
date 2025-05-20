# Function: <code>merge_result</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814491a7)
Location: drivers/pci/pcie/aer/aerdrv.h:82
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a353)
Location: drivers/pci/pcie/aer/aerdrv.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81495407)
Location: drivers/pci/pcie/aer/aerdrv.h:82
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81496613)
Location: drivers/pci/pcie/aer/aerdrv.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6db7)
Location: drivers/pci/pcie/aer/aerdrv.h:83
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7fb3)
Location: drivers/pci/pcie/aer/aerdrv.h:83
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c1747)
Location: drivers/pci/pcie/aer/aerdrv.h:83
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2833)
Location: drivers/pci/pcie/aer/aerdrv.h:83
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502a76)
Location: drivers/pci/pcie/aer/aerdrv.h:84
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81530cac)
Location: drivers/pci/pcie/err.c:27
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81530c20-ffffffff81530c52: merge_result.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8154823c)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff815481b0-ffffffff815481e2: merge_result.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815782bb)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81578240-ffffffff8157826e: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81599a3b)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff815999c0-ffffffff815999ee: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff816393bb)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/pcie/err.c (ffffffff8165fe3b)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/pcie/err.c (ffffffff81642329)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
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
In drivers/pci/pcie/err.c (ffffffff816b300c)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff817db9dd)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff818fd7bd)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81940c4d)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81989ead)
Location: drivers/pci/pcie/err.c:23
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffff800010701290)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffff8000107011c0-ffff800010701234: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (c0898f5c)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
c0898eb8-c0898efc: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffe0004cff98)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffe0004cff06-ffffffe0004cff5a: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d8cb)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8158d850-ffffffff8158d87e: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8157c40b)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8157c390-ffffffff8157c3be: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d78b)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8158d710-ffffffff8158d73e: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815a7c3b)
Location: drivers/pci/pcie/err.c:21
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
Direct callers:
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff815a7bc0-ffffffff815a7bee: merge_result.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
