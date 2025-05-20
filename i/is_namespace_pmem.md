# Function: <code>is_namespace_pmem</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159aec6)
Location: drivers/nvdimm/namespace_devs.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f357e)
Location: drivers/nvdimm/namespace_devs.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffffffff81621e1f)
Location: drivers/nvdimm/namespace_devs.c:70
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_show
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffffffff81636923)
Location: drivers/nvdimm/namespace_devs.c:70
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169e5af)
Location: drivers/nvdimm/namespace_devs.c:70
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816da9d3)
Location: drivers/nvdimm/namespace_devs.c:70
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fc967)
Location: drivers/nvdimm/namespace_devs.c:70
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff81736a2c)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8175a7bb)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8181a253)
Location: drivers/nvdimm/namespace_devs.c:1678
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
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
In drivers/nvdimm/namespace_devs.c (ffffffff81829373)
Location: drivers/nvdimm/namespace_devs.c:1678
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
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
In drivers/nvdimm/namespace_devs.c (ffffffff8180c583)
Location: drivers/nvdimm/namespace_devs.c:1678
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
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
In drivers/nvdimm/namespace_devs.c (ffffffff81896bb3)
Location: drivers/nvdimm/namespace_devs.c:1678
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
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
In drivers/nvdimm/namespace_devs.c (ffffffff819e0112)
Location: drivers/nvdimm/namespace_devs.c:1426
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_dev_to_uuid
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bb3f)
Location: drivers/nvdimm/namespace_devs.c:1418
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_dev_to_uuid
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffffffff81baf0e9)
Location: drivers/nvdimm/namespace_devs.c:1418
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_dev_to_uuid
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c034b9)
Location: drivers/nvdimm/namespace_devs.c:1427
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:namespace_visible
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_dev_to_uuid
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_sector_size
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
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
In drivers/nvdimm/namespace_devs.c (ffff80001095bf8c)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (c000000000a0d318)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca3f2)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170eeab)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e292b)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174dc7b)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff817690fb)
Location: drivers/nvdimm/namespace_devs.c:62
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
```
</details>
</li>
</ul>

## Differences
