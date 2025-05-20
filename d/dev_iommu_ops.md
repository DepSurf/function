# Function: <code>dev_iommu_ops</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81967d18)
Location: include/linux/iommu.h:404
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_sva_get_pasid
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:iommu_deferred_attach
  - drivers/iommu/iommu.c:device_iommu_capable
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:probe_get_default_domain_type
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81ad28b5)
Location: include/linux/iommu.h:446
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:device_iommu_capable
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:probe_get_default_domain_type
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81b21025)
Location: include/linux/iommu.h:453
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:__iommu_group_set_domain_internal
  - drivers/iommu/iommu.c:__iommu_group_set_domain_internal
  - drivers/iommu/iommu.c:device_iommu_capable
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81b77bc5)
Location: drivers/iommu/iommu-priv.h:9
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_dev_disable_feature
  - drivers/iommu/iommu.c:iommu_dev_enable_feature
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:__iommu_domain_alloc_dev
  - drivers/iommu/iommu.c:device_iommu_capable
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_get_default_domain_type
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_deinit_device
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
