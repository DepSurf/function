# Function: <code>dma_pte_present</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81535695)
Location: drivers/iommu/intel-iommu.c:344
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff8158f054)
Location: drivers/iommu/intel-iommu.c:345
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
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
In drivers/iommu/intel-iommu.c (ffffffff815bcb74)
Location: drivers/iommu/intel-iommu.c:345
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
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
In drivers/iommu/intel-iommu.c (ffffffff815d23c4)
Location: drivers/iommu/intel-iommu.c:346
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
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
In drivers/iommu/intel-iommu.c (ffffffff816391a4)
Location: drivers/iommu/intel-iommu.c:344
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
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
In drivers/iommu/intel-iommu.c (ffffffff81674407)
Location: drivers/iommu/intel-iommu.c:345
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
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
In drivers/iommu/intel-iommu.c (ffffffff81692a37)
Location: include/linux/intel-iommu.h:616
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff81694787)
Location: include/linux/intel-iommu.h:616
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
In drivers/iommu/intel-iommu.c (ffffffff816c685c)
Location: include/linux/intel-iommu.h:615
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cd0a9)
Location: include/linux/intel-iommu.h:615
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
In drivers/iommu/intel-iommu.c (ffffffff816eb658)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f0909)
Location: include/linux/intel-iommu.h:621
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
In drivers/iommu/intel/iommu.c (ffffffff817a2795)
Location: include/linux/intel-iommu.h:675
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
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a83bc)
Location: include/linux/intel-iommu.h:675
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
In drivers/iommu/intel/iommu.c (ffffffff817af9f5)
Location: include/linux/intel-iommu.h:687
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
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b426c)
Location: include/linux/intel-iommu.h:687
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
In drivers/iommu/intel/iommu.c (ffffffff817929e5)
Location: include/linux/intel-iommu.h:699
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81797331)
Location: include/linux/intel-iommu.h:699
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
In drivers/iommu/intel/iommu.c (ffffffff8181a7f5)
Location: include/linux/intel-iommu.h:701
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f347)
Location: include/linux/intel-iommu.h:701
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
In drivers/iommu/intel/iommu.c (ffffffff8195af15)
Location: include/linux/intel-iommu.h:674
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f217)
Location: include/linux/intel-iommu.h:674
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
In drivers/iommu/intel/iommu.c (ffffffff81ac2ac2)
Location: drivers/iommu/intel/iommu.h:678
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6d81)
Location: drivers/iommu/intel/iommu.h:678
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
In drivers/iommu/intel/iommu.c (ffffffff81b0f957)
Location: drivers/iommu/intel/iommu.h:772
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13911)
Location: drivers/iommu/intel/iommu.h:772
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
In drivers/iommu/intel/iommu.c (ffffffff81b64592)
Location: drivers/iommu/intel/iommu.h:824
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_read_and_clear_dirty
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b6853f)
Location: drivers/iommu/intel/iommu.h:824
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
In drivers/iommu/intel-iommu.c (ffffffff816b0f88)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b60f9)
Location: include/linux/intel-iommu.h:621
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
In drivers/iommu/intel-iommu.c (ffffffff8168ea88)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693d39)
Location: include/linux/intel-iommu.h:621
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
In drivers/iommu/intel-iommu.c (ffffffff816df318)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e45c9)
Location: include/linux/intel-iommu.h:621
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
In drivers/iommu/intel-iommu.c (ffffffff816f9928)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fec89)
Location: include/linux/intel-iommu.h:621
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
```
</details>
</li>
</ul>

## Differences
