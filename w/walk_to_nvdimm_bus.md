# Function: <code>walk_to_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81597070)
Location: drivers/nvdimm/core.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
```
**Symbols:**

```
ffffffff81597070-ffffffff815970f6: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ecfd0)
Location: drivers/nvdimm/bus.c:249
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
```
**Symbols:**

```
ffffffff815ecfd0-ffffffff815ed056: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619dc0)
Location: drivers/nvdimm/bus.c:251
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
```
**Symbols:**

```
ffffffff81619dc0-ffffffff81619e46: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162de80)
Location: drivers/nvdimm/bus.c:313
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
```
**Symbols:**

```
ffffffff8162de80-ffffffff8162defc: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696630)
Location: drivers/nvdimm/bus.c:314
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
```
**Symbols:**

```
ffffffff81696630-ffffffff816966ac: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2720)
Location: drivers/nvdimm/bus.c:317
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
```
**Symbols:**

```
ffffffff816d2720-ffffffff816d2799: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3e70)
Location: drivers/nvdimm/bus.c:311
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816f3e70-ffffffff816f3ee9: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d4a0)
Location: drivers/nvdimm/bus.c:310
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8172d4a0-ffffffff8172d50e: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81751700)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81751700-ffffffff8175176e: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180ffc0)
Location: drivers/nvdimm/bus.c:313
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8180ffc0-ffffffff8181002d: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181ef00)
Location: drivers/nvdimm/bus.c:313
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8181ef00-ffffffff8181ef6d: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81802220)
Location: drivers/nvdimm/bus.c:312
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81802220-ffffffff8180228d: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:311
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81d0ae46-ffffffff81d0ae5a: walk_to_nvdimm_bus.cold (STB_LOCAL)
ffffffff8188c6e0-ffffffff8188c766: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:302
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81ed32e7-ffffffff81ed32fc: walk_to_nvdimm_bus.cold (STB_LOCAL)
ffffffff819d5b80-ffffffff819d5c38: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:302
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8209a619-ffffffff8209a62e: walk_to_nvdimm_bus.cold (STB_LOCAL)
ffffffff81b50740-ffffffff81b507f8: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:302
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8211b6f9-ffffffff8211b70e: walk_to_nvdimm_bus.cold (STB_LOCAL)
ffffffff81ba3c10-ffffffff81ba3c9e: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:302
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
**Symbols:**

```
ffffffff821f9580-ffffffff821f9595: walk_to_nvdimm_bus.cold (STB_LOCAL)
ffffffff81bf7e00-ffffffff81bf7e8e: walk_to_nvdimm_bus (STB_GLOBAL)
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
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951d88)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffff800010951d88-ffff800010951e20: walk_to_nvdimm_bus (STB_GLOBAL)
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
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fe930)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
c0000000009fe930-c0000000009fea04: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c19a8)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffe0005c19a8-ffffffe0005c1a24: walk_to_nvdimm_bus (STB_GLOBAL)
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
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705df0)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81705df0-ffffffff81705e5e: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9870)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816d9870-ffffffff816d98de: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744bc0)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81744bc0-ffffffff81744c2e: walk_to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvdimm_bus *walk_to_nvdimm_bus(struct device *nd_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81760000)
Location: drivers/nvdimm/bus.c:308
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/core.c:nvdimm_bus_unlock
  - drivers/nvdimm/core.c:nvdimm_bus_lock
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/bus.c:nvdimm_bus_shutdown
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:__nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81760000-ffffffff8176006e: walk_to_nvdimm_bus (STB_GLOBAL)
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
