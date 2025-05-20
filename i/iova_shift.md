# Function: <code>iova_shift</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629773)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664455)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816825e5)
Location: include/linux/iova.h:107
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816b9e05)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dcc05)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8179198b)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81793bc5)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bdb7e)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff817c0155)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0dbe)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff817a32c5)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a891)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff8182cb95)
Location: include/linux/iova.h:106
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196adac)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff8196de35)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad528c)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81ad8775)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b23a3c)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81b26895)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7a7db)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81b7d4d5)
Location: include/linux/iova.h:48
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108ca814)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/iommu/iova.c (ffff8000108cd2fc)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
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
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2655)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680045)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d08c5)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eae55)
Location: include/linux/iova.h:105
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
</details>
</li>
</ul>

## Differences
