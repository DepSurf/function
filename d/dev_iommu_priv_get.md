# Function: <code>dev_iommu_priv_get</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817995db)
Location: include/linux/iommu.h:634
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In drivers/iommu/amd/iommu.c (ffffffff817a7e6b)
Location: include/linux/iommu.h:617
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_fault
  - drivers/iommu/amd/iommu.c:amd_iommu_report_rmp_hw_error
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ac8b5)
Location: include/linux/iommu.h:617
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:auxiliary_link_device
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
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
In drivers/iommu/amd/iommu.c (ffffffff8178717c)
Location: include/linux/iommu.h:578
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff8178f785)
Location: include/linux/iommu.h:578
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
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
In drivers/iommu/amd/iommu.c (ffffffff8180e449)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81817095)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182e4e4)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/iommu/amd/iommu.c (ffffffff8194f61b)
Location: include/linux/iommu.h:647
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff819580d5)
Location: include/linux/iommu.h:647
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ec55)
Location: include/linux/iommu.h:647
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81960f8d)
Location: include/linux/iommu.h:647
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8196f140)
Location: include/linux/iommu.h:647
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/iommu/amd/iommu.c (ffffffff81ab45db)
Location: include/linux/iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf125)
Location: include/linux/iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6725)
Location: include/linux/iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca615)
Location: include/linux/iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81ad9fc5)
Location: include/linux/iommu.h:690
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/iommu/amd/iommu.c (ffffffff81b00e3b)
Location: include/linux/iommu.h:693
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0bb15)
Location: include/linux/iommu.h:693
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13325)
Location: include/linux/iommu.h:693
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17325)
Location: include/linux/iommu.h:693
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b2864f)
Location: include/linux/iommu.h:693
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/iommu/amd/iommu.c (ffffffff81b57cca)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
  - drivers/iommu/amd/iommu.c:amd_iommu_is_attach_deferred
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:amd_iommu_pdev_enable_cap_pri
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b627a5)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_hw_info
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_capable
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc_user
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67f55)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/nested.c (ffffffff81b69075)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c895)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f70f)
Location: include/linux/iommu.h:925
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
