# Function: <code>kmalloc_order_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b27a0)
Location: mm/slab_common.c:1016
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_track_caller
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - crypto/lzo.c:lzo_init
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff811b27a0-ffffffff811b287e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc210)
Location: mm/slab_common.c:1024
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/squashfs/file.c:squashfs_readpage
  - crypto/lzo.c:lzo_init
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff811cc210-ffffffff811cc2dd: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc310)
Location: mm/slab_common.c:1053
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/squashfs/file.c:squashfs_readpage
  - crypto/lzo.c:lzo_alloc_ctx
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
```
**Symbols:**

```
ffffffff811dc310-ffffffff811dc3ab: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e6230)
Location: mm/slab_common.c:1122
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:set_tracer_flag
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/squashfs/file.c:squashfs_readpage
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff811e6230-ffffffff811e62d5: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc470)
Location: mm/slab_common.c:1131
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:set_tracer_flag
  - mm/swapfile.c:SYSC_swapon
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/squashfs/file.c:squashfs_readpage
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff811fc470-ffffffff811fc517: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d5d0)
Location: mm/slab_common.c:1192
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:set_tracer_flag
  - mm/swapfile.c:__do_sys_swapon
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/squashfs/file.c:squashfs_readpage
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff8121d5d0-ffffffff8121d677: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812305c0)
Location: mm/slab_common.c:1239
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:set_tracer_flag
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/squashfs/file.c:squashfs_readpage
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff812305c0-ffffffff81230667: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812405e0)
Location: mm/slab_common.c:1267
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:set_tracer_flag
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/hpet.c:hpet_alloc
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff812405e0-ffffffff8124067e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124eb90)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff8124eb90-ffffffff8124ec2e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d360)
Location: mm/slab_common.c:1339
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:func_add
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/squashfs/file.c:empty_meta_index
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_restore_template_data
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:start_bunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/interconnect/core.c:path_find
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8127d360-ffffffff8127d3fe: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81288d00)
Location: mm/slab_common.c:851
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/audit_tree.c:alloc_chunk
  - kernel/tracepoint.c:func_remove
  - kernel/tracepoint.c:func_add
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/squashfs/file.c:empty_meta_index
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:start_bunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/interconnect/core.c:path_find
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81288d00-ffffffff81288d7e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128e3c0)
Location: mm/slab_common.c:937
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/printk/printk.c:devkmsg_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - fs/squashfs/file.c:empty_meta_index
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff8128e3c0-ffffffff8128e43e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:971
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
  - kernel/printk/printk.c:devkmsg_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - fs/squashfs/file.c:empty_meta_index
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81cbb4cc-ffffffff81cbb4e5: kmalloc_order_trace.cold (STB_LOCAL)
ffffffff812ce2f0-ffffffff812ce375: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:959
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - fs/squashfs/file.c:empty_meta_index
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81e6d079-ffffffff81e6d091: kmalloc_order_trace.cold (STB_LOCAL)
ffffffff8132c390-ffffffff8132c430: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e6858)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - virt/kvm/kvm_main.c:kvm_io_bus_unregister_dev
  - virt/kvm/kvm_main.c:kvm_io_bus_register_dev
  - virt/kvm/arm/arm.c:kvm_arch_alloc_vm
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_create_cb_chain
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffff8000102e6858-ffff8000102e6944: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0509d04)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - kernel/printk/printk.c:devkmsg_open
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/bio-integrity.c:bio_integrity_alloc
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/dma/ti/edma.c:edma_prep_dma_cyclic
  - drivers/dma/ti/edma.c:edma_prep_slave_sg
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
  - drivers/reset/core.c:of_reset_control_array_get
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - sound/core/vmaster.c:_snd_ctl_add_slave
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets
  - net/core/flow_offload.c:flow_rule_alloc
  - net/ipv4/fib_semantics.c:fib_create_info
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
c0509d04-c0509dd4: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a6a50)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/fib_semantics.c:fib_create_info
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
c0000000003a6a50-c0000000003a6b80: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fb9a8)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffe0001fb9a8-ffffffe0001fba5a: kmalloc_order_trace (STB_GLOBAL)
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
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812471e0)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff812471e0-ffffffff8124727e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a190)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff8123a190-ffffffff8123a22e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81244f80)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff81244f80-ffffffff8124501e: kmalloc_order_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81254970)
Location: mm/slab_common.c:1331
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - kernel/printk/printk.c:devkmsg_open
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/tracepoint.c:allocate_probes
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/usb/core/urb.c:usb_alloc_urb
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:rt6_insert_exception
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_inflate.c:__gunzip
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
**Symbols:**

```
ffffffff81254970-ffffffff81254a26: kmalloc_order_trace (STB_GLOBAL)
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
