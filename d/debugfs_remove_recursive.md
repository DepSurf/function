# Function: <code>debugfs_remove_recursive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d7e0)
Location: fs/debugfs/inode.c:584
Inline: True
Direct callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:fini
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8131d7e0-ffffffff8131d99f: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352280)
Location: fs/debugfs/inode.c:647
Inline: True
Direct callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_debug_create_one
```
**Symbols:**

```
ffffffff81352280-ffffffff81352440: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368530)
Location: fs/debugfs/inode.c:647
Inline: True
Direct callers:
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81368530-ffffffff813686f0: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137cba0)
Location: fs/debugfs/inode.c:681
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8137cba0-ffffffff8137cd5f: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1ab0)
Location: fs/debugfs/inode.c:707
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813a1ab0-ffffffff813a1c63: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d15b0)
Location: fs/debugfs/inode.c:730
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_exit
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813d15b0-ffffffff813d1741: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eb8e0)
Location: fs/debugfs/inode.c:733
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813eb8e0-ffffffff813eba71: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814179e0)
Location: fs/debugfs/inode.c:753
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff814179e0-ffffffff81417b6c: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814318a0)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff814318a0-ffffffff81431a2c: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff8000105165b0)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_release
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/altera_edac.c:altr_edac_device_remove
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
```
**Symbols:**

```
ffff8000105165b0-ffff800010516760: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d10dc)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/iommu/tegra-smmu.c:tegra_smmu_remove
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/mtd/mtdcore.c:cleanup_mtd
  - drivers/mtd/mtdcore.c:del_mtd_device
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/usb/musb/musb_debugfs.c:musb_exit_debugfs
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - sound/soc/soc-core.c:snd_soc_exit
  - sound/soc/soc-core.c:soc_cleanup_card_resources
  - sound/soc/soc-core.c:soc_cleanup_component
  - sound/soc/soc-dapm.c:snd_soc_dapm_free
  - sound/soc/soc-pcm.c:dpcm_be_disconnect
  - sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_remove
```
**Symbols:**

```
c06d10dc-c06d125c: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065eee0)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_window_free_dbgdir
  - arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
```
**Symbols:**

```
c00000000065eee0-c00000000065f184: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037fc90)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
```
**Symbols:**

```
ffffffe00037fc90-ffffffe00037fe9c: debugfs_remove_recursive (STB_GLOBAL)
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
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81429e80)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81429e80-ffffffff8142a00c: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8141a900)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/nvdimm/btt.c:nd_btt_exit
  - drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt
  - drivers/nvdimm/btt.c:free_arenas
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8141a900-ffffffff8141aa8c: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81426020)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81426020-ffffffff814261ac: debugfs_remove_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void debugfs_remove_recursive(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143cc10)
Location: fs/debugfs/inode.c:755
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - mm/backing-dev.c:bdi_unregister
  - mm/zswap.c:zswap_debugfs_exit
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_debug_exit
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler
  - drivers/usb/common/common.c:usb_common_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_unregister
  - drivers/opp/debugfs.c:opp_debug_remove_one
  - drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8143cc10-ffffffff8143cd96: debugfs_remove_recursive (STB_GLOBAL)
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
