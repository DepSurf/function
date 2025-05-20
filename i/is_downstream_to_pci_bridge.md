# Function: <code>is_downstream_to_pci_bridge</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c74e5)
Location: drivers/iommu/intel-iommu.c:733
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816c64d0-ffffffff816c650e: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816ea445)
Location: drivers/iommu/intel-iommu.c:744
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816e9440-ffffffff816e947e: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff817a1511)
Location: drivers/iommu/intel/iommu.c:764
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:device_has_rmrr
  - drivers/iommu/intel/iommu.c:device_has_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff817ae9a1)
Location: drivers/iommu/intel/iommu.c:800
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:device_has_rmrr
  - drivers/iommu/intel/iommu.c:device_has_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81791161)
Location: drivers/iommu/intel/iommu.c:816
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81818621)
Location: drivers/iommu/intel/iommu.c:822
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff8195995c)
Location: drivers/iommu/intel/iommu.c:669
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81ac0c35)
Location: drivers/iommu/intel/iommu.c:645
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81b0d4a5)
Location: drivers/iommu/intel/iommu.c:645
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81b61cd5)
Location: drivers/iommu/intel/iommu.c:505
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816aff25)
Location: drivers/iommu/intel-iommu.c:744
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816aef20-ffffffff816aef5e: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8168d875)
Location: drivers/iommu/intel-iommu.c:744
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff8168c880-ffffffff8168c8be: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816de105)
Location: drivers/iommu/intel-iommu.c:744
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816dd100-ffffffff816dd13e: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816f8705)
Location: drivers/iommu/intel-iommu.c:744
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:device_has_rmrr
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff816f75e0-ffffffff816f761e: is_downstream_to_pci_bridge.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
