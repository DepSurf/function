# Function: <code>to_nd_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81599820)
Location: drivers/nvdimm/region_devs.c:69
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:available_size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
**Symbols:**

```
ffffffff81599820-ffffffff8159983c: to_nd_region.part.3 (STB_LOCAL)
ffffffff81599840-ffffffff81599871: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815ef455)
Location: drivers/nvdimm/region_devs.c:157
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff815ef400-ffffffff815ef41c: to_nd_region.part.4 (STB_LOCAL)
ffffffff815ef420-ffffffff815ef44e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161c625)
Location: drivers/nvdimm/region_devs.c:172
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:blk_dpa_busy
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8161c5d0-ffffffff8161c5ec: to_nd_region.part.5 (STB_LOCAL)
ffffffff8161c5f0-ffffffff8161c61e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81631075)
Location: drivers/nvdimm/region_devs.c:176
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81630640-ffffffff8163064d: to_nd_region.part.5 (STB_LOCAL)
ffffffff81630650-ffffffff8163067f: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816998a5)
Location: drivers/nvdimm/region_devs.c:176
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81698e70-ffffffff81698e7d: to_nd_region.part.5 (STB_LOCAL)
ffffffff81698e80-ffffffff81698eaf: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d5b35)
Location: drivers/nvdimm/region_devs.c:176
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816d5100-ffffffff816d510d: to_nd_region.part.7 (STB_LOCAL)
ffffffff816d5110-ffffffff816d513e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f6e45)
Location: drivers/nvdimm/region_devs.c:181
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816f6e00-ffffffff816f6e0d: to_nd_region.part.7 (STB_LOCAL)
ffffffff816f6e10-ffffffff816f6e3e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81730685)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff817328de-ffffffff817328f7: to_nd_region.part.0 (STB_LOCAL)
ffffffff817328f7-ffffffff81732909: to_nd_region.cold (STB_LOCAL)
ffffffff81730650-ffffffff81730674: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81754745)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81754700-ffffffff8175470d: to_nd_region.part.0 (STB_LOCAL)
ffffffff81754710-ffffffff8175473e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81813bf5)
Location: drivers/nvdimm/region_devs.c:143
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81813bd0-ffffffff81813bf0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81822de5)
Location: drivers/nvdimm/region_devs.c:143
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81822dc0-ffffffff81822de0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81805fc5)
Location: drivers/nvdimm/region_devs.c:143
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81805fa0-ffffffff81805fc0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8189285a)
Location: drivers/nvdimm/region_devs.c:143
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8188ff40-ffffffff8188ff60: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819d99b5)
Location: drivers/nvdimm/region_devs.c:140
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff819d9980-ffffffff819d99b0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b54b05)
Location: drivers/nvdimm/region_devs.c:187
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81b54ac0-ffffffff81b54af0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8055)
Location: drivers/nvdimm/region_devs.c:187
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81ba8010-ffffffff81ba8040: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfc2f5)
Location: drivers/nvdimm/region_devs.c:188
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mapping31_show
  - drivers/nvdimm/region_devs.c:mapping30_show
  - drivers/nvdimm/region_devs.c:mapping29_show
  - drivers/nvdimm/region_devs.c:mapping28_show
  - drivers/nvdimm/region_devs.c:mapping27_show
  - drivers/nvdimm/region_devs.c:mapping26_show
  - drivers/nvdimm/region_devs.c:mapping25_show
  - drivers/nvdimm/region_devs.c:mapping24_show
  - drivers/nvdimm/region_devs.c:mapping23_show
  - drivers/nvdimm/region_devs.c:mapping22_show
  - drivers/nvdimm/region_devs.c:mapping21_show
  - drivers/nvdimm/region_devs.c:mapping20_show
  - drivers/nvdimm/region_devs.c:mapping19_show
  - drivers/nvdimm/region_devs.c:mapping18_show
  - drivers/nvdimm/region_devs.c:mapping17_show
  - drivers/nvdimm/region_devs.c:mapping16_show
  - drivers/nvdimm/region_devs.c:mapping15_show
  - drivers/nvdimm/region_devs.c:mapping14_show
  - drivers/nvdimm/region_devs.c:mapping13_show
  - drivers/nvdimm/region_devs.c:mapping12_show
  - drivers/nvdimm/region_devs.c:mapping11_show
  - drivers/nvdimm/region_devs.c:mapping10_show
  - drivers/nvdimm/region_devs.c:mapping9_show
  - drivers/nvdimm/region_devs.c:mapping8_show
  - drivers/nvdimm/region_devs.c:mapping7_show
  - drivers/nvdimm/region_devs.c:mapping6_show
  - drivers/nvdimm/region_devs.c:mapping5_show
  - drivers/nvdimm/region_devs.c:mapping4_show
  - drivers/nvdimm/region_devs.c:mapping3_show
  - drivers/nvdimm/region_devs.c:mapping2_show
  - drivers/nvdimm/region_devs.c:mapping1_show
  - drivers/nvdimm/region_devs.c:mapping0_show
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:persistence_domain_show
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:align_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81bfc2b0-ffffffff81bfc2e0: to_nd_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff8000109553a4)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffff800010955308-ffff800010955324: to_nd_region.part.0 (STB_LOCAL)
ffff800010955328-ffff80001095537c: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a02fa0)
Location: drivers/nvdimm/region_devs.c:173
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
c000000000a02fa0-c000000000a02fd4: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c49d6)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffe0005c4956-ffffffe0005c4972: to_nd_region.part.0 (STB_LOCAL)
ffffffe0005c4972-ffffffe0005c49b8: to_nd_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81708e35)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81708df0-ffffffff81708dfd: to_nd_region.part.0 (STB_LOCAL)
ffffffff81708e00-ffffffff81708e2e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dc8b5)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable
  - drivers/acpi/nfit/core.c:range_index_show
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/nvdimm/pmem.c:nd_pmem_shutdown
  - drivers/nvdimm/pmem.c:nd_pmem_remove
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816dc870-ffffffff816dc87d: to_nd_region.part.0 (STB_LOCAL)
ffffffff816dc880-ffffffff816dc8ae: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81747c05)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81747bc0-ffffffff81747bcd: to_nd_region.part.0 (STB_LOCAL)
ffffffff81747bd0-ffffffff81747bfe: to_nd_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_region *to_nd_region(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763085)
Location: drivers/nvdimm/region_devs.c:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:mapping_visible
  - drivers/nvdimm/region_devs.c:mappingN
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:resource_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:read_only_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:mappings_show
  - drivers/nvdimm/region_devs.c:deep_flush_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nstype_show
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81763040-ffffffff8176304d: to_nd_region.part.0 (STB_LOCAL)
ffffffff81763050-ffffffff8176307e: to_nd_region (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
