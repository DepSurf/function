# Function: <code>nvdimm_bus_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81597130)
Location: drivers/nvdimm/core.c:39
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
**Symbols:**

```
ffffffff81597130-ffffffff81597151: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815eb790)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_add_poison
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff815eb790-ffffffff815eb7b1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816185a0)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_clear_from_poison_list
  - drivers/nvdimm/core.c:nvdimm_bus_add_poison
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816185a0-ffffffff816185c1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162c420)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8162c420-ffffffff8162c441: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816950c0)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816950c0-ffffffff816950e1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d1190)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816d1190-ffffffff816d11b1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2830)
Location: drivers/nvdimm/core.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816f2830-ffffffff816f2851: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172bdb0)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8172bdb0-ffffffff8172bdd1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8174ffd0)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8174ffd0-ffffffff8174fff1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180ee92)
Location: drivers/nvdimm/core.c:32
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8180e720-ffffffff8180e741: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181da72)
Location: drivers/nvdimm/core.c:32
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8181d290-ffffffff8181d2b1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81800ce2)
Location: drivers/nvdimm/core.c:32
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81800620-ffffffff81800641: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188b0f2)
Location: drivers/nvdimm/core.c:32
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8188aa20-ffffffff8188aa41: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d47dd)
Location: drivers/nvdimm/core.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff819d3de0-ffffffff819d3e09: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4f07d)
Location: drivers/nvdimm/core.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81b4e570-ffffffff81b4e599: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba24cd)
Location: drivers/nvdimm/core.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81ba19d0-ffffffff81ba19f9: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf668d)
Location: drivers/nvdimm/core.c:33
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nvdimm_delete
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81bf5b60-ffffffff81bf5b89: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff80001094fbf8)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffff80001094fbf8-ffff80001094fc30: nvdimm_bus_unlock (STB_GLOBAL)
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
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fc310)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
c0000000009fc310-c0000000009fc358: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c0088)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffe0005c0088-ffffffe0005c00c0: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff817046c0)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff817046c0-ffffffff817046e1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d8140)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816d8140-ffffffff816d8161: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81743490)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81743490-ffffffff817434b1: nvdimm_bus_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvdimm_bus_unlock(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175e8e0)
Location: drivers/nvdimm/core.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/region_devs.c:dax_seed_show
  - drivers/nvdimm/region_devs.c:pfn_seed_show
  - drivers/nvdimm/region_devs.c:btt_seed_show
  - drivers/nvdimm/region_devs.c:namespace_seed_show
  - drivers/nvdimm/region_devs.c:init_namespaces_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/security.c:nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8175e8e0-ffffffff8175e901: nvdimm_bus_unlock (STB_GLOBAL)
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
