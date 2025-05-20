# Function: <code>debugfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d740)
Location: fs/debugfs/inode.c:551
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/char/virtio_console.c:unplug_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff8131d740-ffffffff8131d7de: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813521e0)
Location: fs/debugfs/inode.c:615
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/char/virtio_console.c:unplug_port
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff813521e0-ffffffff81352280: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368490)
Location: fs/debugfs/inode.c:615
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/char/virtio_console.c:unplug_port
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81368490-ffffffff81368530: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137caf0)
Location: fs/debugfs/inode.c:649
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/char/virtio_console.c:unplug_port
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_unregister_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_unregister_driver
```
**Symbols:**

```
ffffffff8137caf0-ffffffff8137cb95: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1a10)
Location: fs/debugfs/inode.c:677
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff813a1a10-ffffffff813a1aa8: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0e40)
Location: fs/debugfs/inode.c:700
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff813d0e40-ffffffff813d0eb3: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eb5b0)
Location: fs/debugfs/inode.c:703
Inline: True
Direct callers:
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff813eb5b0-ffffffff813eb623: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81417690)
Location: fs/debugfs/inode.c:723
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81417690-ffffffff81417702: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81431550)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
ffffffff81431550-ffffffff814315c2: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814810f0)
Location: fs/debugfs/inode.c:697
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_migrate_dentry
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:create_debugfs_nodes
```
**Symbols:**

```
ffffffff814810f0-ffffffff8148114f: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149e770)
Location: fs/debugfs/inode.c:722
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:destroy_regulator
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_migrate_dentry
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:create_debugfs_nodes
```
**Symbols:**

```
ffffffff8149e770-ffffffff8149e7cf: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a4730)
Location: fs/debugfs/inode.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_remove
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff814a4730-ffffffff814a478f: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fc640)
Location: fs/debugfs/inode.c:726
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/slub.c:debugfs_slab_release
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff814fc640-ffffffff814fc69f: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158ccc0)
Location: fs/debugfs/inode.c:736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/slub.c:debugfs_slab_release
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:_regulator_put
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_aggregate_device
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
  - drivers/hte/hte.c:hte_ts_put
```
**Symbols:**

```
ffffffff8158ccc0-ffffffff8158cd36: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81633ff7)
Location: fs/debugfs/inode.c:759
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - mm/slub.c:debugfs_slab_release
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_dev_release
  - drivers/regulator/core.c:_regulator_put
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
  - drivers/hte/hte.c:hte_ts_put
```
**Symbols:**

```
ffffffff81633620-ffffffff81633696: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166c307)
Location: fs/debugfs/inode.c:759
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/sched/build_utility.c:sched_verbose_write
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - crypto/jitterentropy-testing.c:jent_testing_exit
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/phy/phy-core.c:phy_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/regulator/core.c:regulator_dev_release
  - drivers/regulator/core.c:_regulator_put
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
  - drivers/hte/hte.c:hte_ts_put
```
**Symbols:**

```
ffffffff8166b920-ffffffff8166b996: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a67a7)
Location: fs/debugfs/inode.c:806
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/sched/build_utility.c:sched_verbose_write
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/backing-dev.c:bdi_unregister
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - lib/error-inject.c:init_error_injection
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/phy/phy-core.c:phy_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_unregister
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/pmdomain/core.c:genpd_debug_exit
  - drivers/regulator/core.c:regulator_dev_release
  - drivers/regulator/core.c:_regulator_put
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_remove
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_crtc_remove
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_remove
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_unregister
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_fini
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_remove_files
  - drivers/accel/drm_accel.c:accel_core_exit
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/ptp/ptp_chardev.c:ptp_release
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
  - drivers/ras/cec.c:cec_init
  - drivers/hte/hte.c:hte_ts_put
```
**Symbols:**

```
ffffffff816a5cd0-ffffffff816a5d46: debugfs_remove (STB_GLOBAL)
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
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010516278)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/firmware/ti_sci.c:ti_sci_remove
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
ffff800010516278-ffff8000105162f8: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d1070)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
c06d1070-c06d10dc: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065ee20)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
c00000000065ee20-c00000000065eee0: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037f9be)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
```
**Symbols:**

```
ffffffe00037f9be-ffffffe00037fa42: debugfs_remove (STB_GLOBAL)
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
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81429b30)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
ffffffff81429b30-ffffffff81429ba2: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8141a5b0)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff8141a5b0-ffffffff8141a622: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81425cd0)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81425cd0-ffffffff81425d42: debugfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143cb90)
Location: fs/debugfs/inode.c:725
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_remove_buf_file_callback
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - lib/error-inject.c:init_error_injection
  - drivers/acpi/acpi_dbg.c:acpi_aml_exit
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/component.c:free_master
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file
```
**Symbols:**

```
ffffffff8143cb90-ffffffff8143cc02: debugfs_remove (STB_GLOBAL)
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
