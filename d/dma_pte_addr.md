# Function: <code>dma_pte_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815381ac)
Location: drivers/iommu/intel-iommu.c:334
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158cc9c)
Location: drivers/iommu/intel-iommu.c:335
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ba3dc)
Location: drivers/iommu/intel-iommu.c:335
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf8de)
Location: drivers/iommu/intel-iommu.c:336
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
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
In drivers/iommu/intel-iommu.c (ffffffff8163666e)
Location: drivers/iommu/intel-iommu.c:334
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
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
In drivers/iommu/intel-iommu.c (ffffffff81671bde)
Location: drivers/iommu/intel-iommu.c:335
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8169050e)
Location: include/linux/intel-iommu.h:606
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169476b)
Location: include/linux/intel-iommu.h:606
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c86b5)
Location: include/linux/intel-iommu.h:605
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cd09c)
Location: include/linux/intel-iommu.h:605
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eb676)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f08fc)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff817a27b5)
Location: include/linux/intel-iommu.h:664
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a83b5)
Location: include/linux/intel-iommu.h:664
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff817afa15)
Location: include/linux/intel-iommu.h:676
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b4265)
Location: include/linux/intel-iommu.h:676
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff81792a05)
Location: include/linux/intel-iommu.h:688
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179732a)
Location: include/linux/intel-iommu.h:688
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff8181a815)
Location: include/linux/intel-iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f340)
Location: include/linux/intel-iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff8195af41)
Location: include/linux/intel-iommu.h:663
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f210)
Location: include/linux/intel-iommu.h:663
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff81ac2aee)
Location: drivers/iommu/intel/iommu.h:667
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6d7a)
Location: drivers/iommu/intel/iommu.h:667
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff81b0f983)
Location: drivers/iommu/intel/iommu.h:761
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1390a)
Location: drivers/iommu/intel/iommu.h:761
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
In drivers/iommu/intel/iommu.c (ffffffff81b64273)
Location: drivers/iommu/intel/iommu.h:813
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b68538)
Location: drivers/iommu/intel/iommu.h:813
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0fa6)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b60ec)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168eaa6)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693d2c)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816df336)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e45bc)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f9946)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fec7c)
Location: include/linux/intel-iommu.h:611
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
</ul>

## Differences
