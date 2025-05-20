# Function: <code>xa_empty</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81793082)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
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
In kernel/exit.c (ffffffff810a97cf)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In fs/exec.c (ffffffff81329acb)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/io_uring.c (ffffffff8139a963)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_free
```
```
In drivers/acpi/scan.c (ffffffff816a6e0e)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del
```
```
In drivers/iommu/ioasid.c (ffffffff817bfac2)
Location: include/linux/xarray.h:401
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
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
In mm/truncate.c (ffffffff812703b9)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8137455c)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
```
In fs/io_uring.c (ffffffff81397f71)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:__io_uring_free
```
```
In fs/dax.c (ffffffff813a64da)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In block/blk-settings.c (ffffffff8156d4a0)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
```
```
In drivers/acpi/scan.c (ffffffff81689a9e)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del
```
```
In drivers/iommu/ioasid.c (ffffffff817a2ce2)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
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
In mm/truncate.c (ffffffff812ae039)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff8139650a)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/io_uring.c (ffffffff813e3ac2)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:__io_uring_free
```
```
In fs/dax.c (ffffffff813f5f4a)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81410956)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff815c42aa)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
```
In drivers/acpi/scan.c (ffffffff816fef7e)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del
```
```
In drivers/iommu/ioasid.c (ffffffff8182c022)
Location: include/linux/xarray.h:403
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
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
In kernel/irq/msi.c (ffffffff8116e175)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_data_release
```
```
In mm/truncate.c (ffffffff8130757d)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff81417a6b)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff81469b13)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff814862a3)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff8166ebdb)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
```
In io_uring/io_uring.c (ffffffff81e901b9)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:__io_uring_free
```
```
In drivers/acpi/scan.c (ffffffff8182c9a7)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del_work_fn
```
```
In drivers/iommu/ioasid.c (ffffffff8196d03e)
Location: include/linux/xarray.h:404
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
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
In kernel/irq/msi.c (ffffffff811a5429)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_data_release
```
```
In mm/truncate.c (ffffffff813716a8)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff814a320b)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff814fa263)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81519b63)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff81729ec8)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
```
In io_uring/fdinfo.c (ffffffff8179b604)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/tctx.c (ffffffff8179b9d6)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_free
```
```
In drivers/acpi/scan.c (ffffffff8195f646)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del_work_fn
```
```
In drivers/iommu/iommu.c (ffffffff81ad0b19)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
```
```
In drivers/iommu/ioasid.c (ffffffff81ad779e)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In net/core/devlink.c (ffffffff81e2c47b)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_free
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
In kernel/irq/msi.c (ffffffff811b7639)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_data_release
```
```
In mm/truncate.c (ffffffff813a37b8)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff814d835b)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff815316e2)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81551453)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff81766238)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
```
In io_uring/fdinfo.c (ffffffff817dc729)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In io_uring/tctx.c (ffffffff817dcb06)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_free
```
```
In drivers/acpi/scan.c (ffffffff819a5a46)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del_work_fn
```
```
In drivers/iommu/iommu.c (ffffffff81b1e5f9)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
```
```
In net/devlink/core.c (ffffffff8204242a)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_free
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
In kernel/irq/msi.c (ffffffff811c74f9)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_data_release
```
```
In mm/truncate.c (ffffffff813cd358)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff8150ab3b)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff815665c2)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81587353)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff817a7cf8)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
```
In io_uring/fdinfo.c (ffffffff81820caa)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/tctx.c (ffffffff81820da6)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_free
```
```
In drivers/acpi/scan.c (ffffffff819ee3c6)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_del_work_fn
```
```
In drivers/iommu/iommu.c (ffffffff81b768fd)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb7385)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_device_put
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eb9c65)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
```
```
In net/devlink/core.c (ffffffff8210105a)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_free
```
```
In net/devlink/dev.c (ffffffff821040ba)
Location: include/linux/xarray.h:405
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_reload
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
