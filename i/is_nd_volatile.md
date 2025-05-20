# Function: <code>is_nd_volatile</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8163159d)
Location: drivers/nvdimm/region_devs.c:171
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81631de0-ffffffff81631dfd: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699f30)
Location: drivers/nvdimm/region_devs.c:171
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8169a740-ffffffff8169a75d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6095)
Location: drivers/nvdimm/region_devs.c:171
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816d69f0-ffffffff816d6a0d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7db5)
Location: drivers/nvdimm/region_devs.c:176
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816f87d0-ffffffff816f87ed: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817314af)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81731e90-ffffffff81731ead: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81754655)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81756000-ffffffff8175601d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81813295)
Location: drivers/nvdimm/region_devs.c:852
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81815910-ffffffff8181592d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818224a5)
Location: drivers/nvdimm/region_devs.c:852
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81824b00-ffffffff81824b1d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818057d5)
Location: drivers/nvdimm/region_devs.c:859
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81807e90-ffffffff81807ead: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8188fef5)
Location: drivers/nvdimm/region_devs.c:859
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81892630-ffffffff8189264d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819d9925)
Location: drivers/nvdimm/region_devs.c:802
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff819dc800-ffffffff819dc823: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b54a55)
Location: drivers/nvdimm/region_devs.c:847
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81b57e40-ffffffff81b57e63: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba7fa5)
Location: drivers/nvdimm/region_devs.c:847
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81bab3b0-ffffffff81bab3d3: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfc245)
Location: drivers/nvdimm/region_devs.c:848
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:__reserve_free_pmem
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81bff6f0-ffffffff81bff713: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010955220)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
**Symbols:**

```
ffff800010957380-ffff8000109573c0: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a02f50)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
c000000000a05310-c000000000a05358: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c47ae)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
**Symbols:**

```
ffffffe0005c6402-ffffffe0005c6436: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81708d45)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8170a6f0-ffffffff8170a70d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dc7c5)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816de170-ffffffff816de18d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81747b15)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff817494c0-ffffffff817494dd: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_volatile(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81762f15)
Location: drivers/nvdimm/region_devs.c:168
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81764940-ffffffff8176495d: is_nd_volatile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
