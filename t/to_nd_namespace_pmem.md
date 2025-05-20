# Function: <code>to_nd_namespace_pmem</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159b9bb)
Location: include/linux/nd.h:98
Inline: True
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f10c5)
Location: include/linux/nd.h:113
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff816202ef)
Location: include/linux/nd.h:115
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff81634de6)
Location: include/linux/nd.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169d768)
Location: include/linux/nd.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff816dbe06)
Location: include/linux/nd.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fddab)
Location: include/linux/nd.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff817379bc)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8175b791)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8181afb0)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
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
In drivers/nvdimm/namespace_devs.c (ffffffff8182a0d0)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
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
In drivers/nvdimm/namespace_devs.c (ffffffff8180d3af)
Location: include/linux/nd.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
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
In drivers/nvdimm/namespace_devs.c (ffffffff8189791f)
Location: include/linux/nd.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_show
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
In drivers/nvdimm/namespace_devs.c (ffffffff819df7e1)
Location: include/linux/nd.h:152
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5ad18)
Location: include/linux/nd.h:152
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff81bae57b)
Location: include/linux/nd.h:152
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c028eb)
Location: include/linux/nd.h:152
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095ce10)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0e5d0)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cb126)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
```
</details>
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170fe81)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e3901)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174ec51)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8176a0d1)
Location: include/linux/nd.h:120
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:cmp_dpa
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
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
```
</details>
</li>
</ul>

## Differences
