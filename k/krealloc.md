# Function: <code>krealloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2c40)
Location: mm/slab_common.c:1233
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:__bioset_create
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/label.c:init_labels
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/core/dev.c:dev_set_alias
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff811b2c40-ffffffff811b2cfa: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc6a0)
Location: mm/slab_common.c:1286
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:__bioset_create
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/label.c:init_labels
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/core/dev.c:dev_set_alias
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff811cc6a0-ffffffff811cc763: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc770)
Location: mm/slab_common.c:1315
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:__bioset_create
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/core/dev.c:dev_set_alias
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff811dc770-ffffffff811dc833: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e66b0)
Location: mm/slab_common.c:1403
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_create
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/core/dev.c:dev_set_alias
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff811e66b0-ffffffff811e6773: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc8f0)
Location: mm/slab_common.c:1445
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_create
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff811fc8f0-ffffffff811fc9b3: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121da40)
Location: mm/slab_common.c:1506
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff8121da40-ffffffff8121dae5: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230a30)
Location: mm/slab_common.c:1553
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff81230a30-ffffffff81230acb: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240c30)
Location: mm/slab_common.c:1643
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff81240c30-ffffffff81240ce7: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124f1e0)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff8124f1e0-ffffffff8124f297: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127da20)
Location: mm/slab_common.c:1693
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/bio.c:bio_find_or_create_slab
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - drivers/interconnect/core.c:icc_link_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff8127da20-ffffffff8127dacd: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81288120)
Location: mm/slab_common.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bio_find_or_create_slab
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - drivers/interconnect/core.c:icc_link_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff81288120-ffffffff812881ca: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128cdb0)
Location: mm/slab_common.c:1198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - drivers/interconnect/core.c:icc_link_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff8128cdb0-ffffffff8128ce5a: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812ccc40)
Location: mm/slab_common.c:1232
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:realloc_array
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - fs/ext4/fast_commit.c:ext4_fc_record_regions
  - security/apparmor/policy_unpack.c:deflate_compress
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_register_dev_region
  - drivers/interconnect/core.c:icc_link_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff812ccc40-ffffffff812ccd01: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132b350)
Location: mm/slab_common.c:1209
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__btf_populate_kfunc_set
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - fs/ext4/fast_commit.c:ext4_fc_record_regions
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_register_dev_region
  - drivers/interconnect/core.c:icc_link_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff8132b350-ffffffff8132b430: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a2630)
Location: mm/slab_common.c:1389
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/bpf_trace.c:module_callback
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - fs/ext4/fast_commit.c:ext4_fc_record_regions
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/interconnect/core.c:icc_link_create
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff813a2630-ffffffff813a272a: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d5af0)
Location: mm/slab_common.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - fs/ext4/fast_commit.c:ext4_fc_record_regions
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/interconnect/core.c:icc_link_create
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff813d5af0-ffffffff813d5bea: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813ff7c0)
Location: mm/slab_common.c:1211
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/bpf/core.c:bpf_jit_add_poke_descriptor
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:cn_vprintf
  - fs/ext4/fast_commit.c:ext4_fc_record_regions
  - security/apparmor/policy_unpack.c:compress_zstd
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_private_obj_state
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
  - drivers/gpu/drm/drm_edid.c:edid_filter_invalid_blocks
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_xrgb8888_to_mono
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_map_msg
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/interconnect/core.c:icc_link_create
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/netlink/policy.c:add_policy
```
**Symbols:**

```
ffffffff813ff7c0-ffffffff813ff8ba: krealloc (STB_GLOBAL)
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
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e5568)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffff8000102e5568-ffff8000102e5640: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050a418)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/bpf/verifier.c:push_jmp_history
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/coredump.c:expand_corename
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_add
  - sound/soc/soc-dapm.c:dapm_create_or_share_kcontrol
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
c050a418-c050a4c4: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a7520)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_alloc_mem_ranges
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
c0000000003a7520-c0000000003a7680: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc03a)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffe0001fc03a-ffffffe0001fc0ce: krealloc (STB_GLOBAL)
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
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81247830)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff81247830-ffffffff812478e7: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a7e0)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff8123a7e0-ffffffff8123a897: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812455d0)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff812455d0-ffffffff81245687: krealloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *krealloc(const void *p, size_t new_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81254fe0)
Location: mm/slab_common.c:1707
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - kernel/trace/trace.c:create_trace_option_files
  - fs/xattr.c:vfs_getxattr_alloc
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - block/bio.c:bioset_init
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_info_cap_add
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region
  - net/netlink/af_netlink.c:netlink_realloc_groups
```
**Symbols:**

```
ffffffff81254fe0-ffffffff81255097: krealloc (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
