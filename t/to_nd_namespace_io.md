# Function: <code>to_nd_namespace_io</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159b9bb)
Location: include/linux/nd.h:93
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:93
Inline: True
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f10c5)
Location: include/linux/nd.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:108
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:108
Inline: True
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
In drivers/nvdimm/namespace_devs.c (ffffffff816202ef)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:110
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:110
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:123
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81634de6)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:123
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:123
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169d768)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:123
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d1ca4)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dbe06)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff816debcf)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e0b68)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff816f3334)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fddab)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff81700f9f)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81702eeb)
Location: include/linux/nd.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff8172c88d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817379bc)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff8173ae1f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173cc8f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff81750aad)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175b791)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff8175eaef)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81760a7f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff8180f31d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181afb0)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:devm_namespace_disable
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:115
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff818207c5)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:__nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff8181e25d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8182a0d0)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:devm_namespace_disable
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:115
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f6b5)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:__nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff818015c0)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180d3af)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:devm_namespace_disable
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:116
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81812b19)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff8188ba50)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8189791f)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:devm_namespace_disable
  - drivers/nvdimm/namespace_devs.c:devm_namespace_enable
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:116
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189d1a9)
Location: include/linux/nd.h:116
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819df7e1)
Location: include/linux/nd.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:147
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5ad18)
Location: include/linux/nd.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:147
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bae57b)
Location: include/linux/nd.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:147
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c028eb)
Location: include/linux/nd.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (0)
Location: include/linux/nd.h:147
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/nd.h:147
Inline: True
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
In drivers/nvdimm/bus.c (ffff8000109509e8)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ce10)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffff800010960334)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fd528)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0e5d0)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (c000000000a131c4)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a161dc)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c0ba8)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cb126)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffe0005cddf4)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In drivers/nvdimm/bus.c (ffffffff8170519d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170fe81)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff817131df)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8171516f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff816d8c1d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e3901)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff816e6c5f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8bef)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb4c0)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:nd_pmem_probe
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/btt.c (ffffffff816ee4af)
Location: include/linux/nd.h:115
Inline: True
```
```
In drivers/dax/pmem/core.c (ffffffff816f20de)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/dax/pmem/core.c:__dax_pmem_probe
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
In drivers/nvdimm/bus.c (ffffffff81743f6d)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ec51)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff81751faf)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753f3f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
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
In drivers/nvdimm/bus.c (ffffffff8175f3bd)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176a0d1)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/namespace_devs.c:namespace_io_release
```
```
In drivers/nvdimm/claim.c (ffffffff8176d42f)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f3af)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
```
</details>
</li>
</ul>

## Differences
