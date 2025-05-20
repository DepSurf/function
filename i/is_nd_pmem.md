# Function: <code>is_nd_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159a02f)
Location: drivers/nvdimm/region_devs.c:59
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
**Symbols:**

```
ffffffff8159a980-ffffffff8159a99f: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815eff92)
Location: drivers/nvdimm/region_devs.c:147
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/bus.c:pmem_active
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815f0960-ffffffff815f097f: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161d172)
Location: drivers/nvdimm/region_devs.c:162
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/bus.c:pmem_active
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:blk_dpa_busy
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8161d920-ffffffff8161d93f: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816305c8)
Location: drivers/nvdimm/region_devs.c:161
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_has_cache
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81631da0-ffffffff81631dbd: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81698df8)
Location: drivers/nvdimm/region_devs.c:161
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_has_cache
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
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
ffffffff8169a700-ffffffff8169a71d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d607b)
Location: drivers/nvdimm/region_devs.c:161
Inline: True
Inline callers:
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
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
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
ffffffff816d69b0-ffffffff816d69cd: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7d9b)
Location: drivers/nvdimm/region_devs.c:166
Inline: True
Inline callers:
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
ffffffff816f8790-ffffffff816f87ad: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817305c5)
Location: drivers/nvdimm/region_devs.c:158
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
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
ffffffff81731e50-ffffffff81731e6d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81754672)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffff81755fc0-ffffffff81755fdd: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818132b2)
Location: drivers/nvdimm/region_devs.c:842
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
ffffffff818158d0-ffffffff818158ed: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818224c2)
Location: drivers/nvdimm/region_devs.c:842
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
ffffffff81824ac0-ffffffff81824add: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818057f2)
Location: drivers/nvdimm/region_devs.c:849
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
ffffffff81807e50-ffffffff81807e6d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8188ff12)
Location: drivers/nvdimm/region_devs.c:849
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
ffffffff818925f0-ffffffff8189260d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819d9942)
Location: drivers/nvdimm/region_devs.c:797
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:is_nvdimm_sync
  - drivers/nvdimm/region_devs.c:nvdimm_has_cache
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
ffffffff819dc7d0-ffffffff819dc7f3: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b54a72)
Location: drivers/nvdimm/region_devs.c:842
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
ffffffff81b57e00-ffffffff81b57e23: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba7fc2)
Location: drivers/nvdimm/region_devs.c:842
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
ffffffff81bab370-ffffffff81bab393: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfc262)
Location: drivers/nvdimm/region_devs.c:843
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
ffffffff81bff6b0-ffffffff81bff6d3: is_nd_pmem (STB_GLOBAL)
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
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff80001095523c)
Location: drivers/nvdimm/region_devs.c:158
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
ffff8000109572f0-ffff800010957334: is_nd_pmem (STB_GLOBAL)
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
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a02f70)
Location: drivers/nvdimm/region_devs.c:158
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
c000000000a05270-c000000000a052b8: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c47c0)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffe0005c639a-ffffffe0005c63ce: is_nd_pmem (STB_GLOBAL)
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
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81708d62)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffff8170a6b0-ffffffff8170a6cd: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dc7e2)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffff816de130-ffffffff816de14d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81747b32)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffff81749480-ffffffff8174949d: is_nd_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pmem(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81762f32)
Location: drivers/nvdimm/region_devs.c:158
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
ffffffff81764900-ffffffff8176491d: is_nd_pmem (STB_GLOBAL)
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
