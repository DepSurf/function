# Function: <code>debugfs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131dca0)
Location: fs/debugfs/inode.c:409
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/backing-dev.c:bdi_register
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_init
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
ffffffff8131dca0-ffffffff8131dd98: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352740)
Location: fs/debugfs/inode.c:469
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
ffffffff81352740-ffffffff8135283e: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813689f0)
Location: fs/debugfs/inode.c:469
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
ffffffff813689f0-ffffffff81368aee: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137d080)
Location: fs/debugfs/inode.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8137d080-ffffffff8137d17e: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1f90)
Location: fs/debugfs/inode.c:506
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813a1f90-ffffffff813a208e: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d11e0)
Location: fs/debugfs/inode.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_init
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813d11e0-ffffffff813d12d2: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eba80)
Location: fs/debugfs/inode.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813eba80-ffffffff813ebb7b: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81418004-ffffffff81418023: debugfs_create_dir.cold (STB_LOCAL)
ffffffff81417b70-ffffffff81417c66: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81431ec4-ffffffff81431ee3: debugfs_create_dir.cold (STB_LOCAL)
ffffffff81431a30-ffffffff81431b26: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/power/energy_model.c:em_debug_init
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_debugfs_init
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81481afc-ffffffff81481b1b: debugfs_create_dir.cold (STB_LOCAL)
ffffffff81481310-ffffffff8148141a: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/energy_model.c:em_debug_init
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_debugfs_init
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81bef86f-ffffffff81bef88e: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8149ed30-ffffffff8149eea4: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81be1918-ffffffff81be1937: debugfs_create_dir.cold (STB_LOCAL)
ffffffff814a4d10-ffffffff814a4e84: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efi_debugfs_init
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81cd2503-ffffffff81cd2536: debugfs_create_dir.cold (STB_LOCAL)
ffffffff814fce00-ffffffff814fcfa0: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mce_get_debugfs_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/hte/hte.c:hte_register_chip
  - drivers/hte/hte.c:__hte_req_ts
  - drivers/hte/hte.c:hte_subsys_dbgfs_init
```
**Symbols:**

```
ffffffff81e85648-ffffffff81e8567c: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8158d630-ffffffff8158d7d7: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/hte/hte.c:hte_register_chip
  - drivers/hte/hte.c:__hte_req_ts
  - drivers/hte/hte.c:hte_subsys_dbgfs_init
```
**Symbols:**

```
ffffffff82072a55-ffffffff82072a6a: debugfs_create_dir.cold (STB_LOCAL)
ffffffff816344e0-ffffffff816346da: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_setup
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:debugfs_slab_add
  - crypto/jitterentropy-testing.c:jent_testing_init
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/hte/hte.c:hte_register_chip
  - drivers/hte/hte.c:__hte_req_ts
  - drivers/hte/hte.c:hte_subsys_dbgfs_init
```
**Symbols:**

```
ffffffff820f26b9-ffffffff820f26ce: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8166c7f0-ffffffff8166c9ea: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:595
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs
  - arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_debug_init
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:debugfs_slab_add
  - mm/zswap.c:zswap_debugfs_init
  - block/blk-core.c:blk_dev_init
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/pmdomain/core.c:genpd_debug_init
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/base/component.c:component_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_crtc_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_init
  - drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add
  - drivers/accel/drm_accel.c:accel_core_init
  - drivers/gpu/drm/bridge/panel.c:panel_bridge_debugfs_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_chardev.c:ptp_open
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/hte/hte.c:hte_register_chip
  - drivers/hte/hte.c:__hte_req_ts
  - drivers/hte/hte.c:hte_subsys_dbgfs_init
```
**Symbols:**

```
ffffffff821cf932-ffffffff821cf947: debugfs_create_dir.cold (STB_LOCAL)
ffffffff816a6990-ffffffff816a6bbf: debugfs_create_dir (STB_GLOBAL)
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
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010516760)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
ffff800010516760-ffff80001051687c: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d1530)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
  - arch/arm/mach-omap2/pm-debug.c:pwrdms_setup
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_class_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/mtd/mtdcore.c:init_mtd
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/usb/musb/musb_debugfs.c:musb_init_debugfs
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:bpmp_populate_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/ras/debugfs.c:ras_debugfs_init
  - sound/soc/soc-core.c:snd_soc_init
  - sound/soc/soc-core.c:snd_soc_instantiate_card
  - sound/soc/soc-core.c:soc_probe_component
  - sound/soc/soc-core.c:soc_probe_component
  - sound/soc/soc-dapm.c:snd_soc_dapm_debugfs_init
  - sound/soc/soc-pcm.c:soc_dpcm_debugfs_add
  - sound/soc/soc-pcm.c:dpcm_add_paths
  - sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_create
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
**Symbols:**

```
c06d1530-c06d1650: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065f6d0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:powerpc_debugfs_init
  - arch/powerpc/platforms/powernv/opal-lpc.c:__machine_initcall_powernv_opal_lpc_init_debugfs
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/memtrace.c:__machine_initcall_powernv_memtrace_init
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_instance_init_dbgdir
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir
  - arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vpa_debugfs_init
  - arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
c00000000065f6d0-c00000000065f830: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037fe9c)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/trace/blktrace.c:__blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/ras/debugfs.c:ras_debugfs_init
```
**Symbols:**

```
ffffffe00037fe9c-ffffffe00037ff98: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8142a4a4-ffffffff8142a4c3: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8142a010-ffffffff8142a106: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/nvdimm/btt.c:nd_btt_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8141af24-ffffffff8141af43: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8141aa90-ffffffff8141ab86: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81426644-ffffffff81426663: debugfs_create_dir.cold (STB_LOCAL)
ffffffff814261b0-ffffffff814262a6: debugfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kdebugfs.c:arch_kdebugfs_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_class_init
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - block/blk-core.c:blk_dev_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/acpi/debugfs.c:acpi_debugfs_init
  - drivers/acpi/apei/apei-base.c:apei_get_debugfs_dir
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:init
  - drivers/base/component.c:component_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_initcall
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/dma-buf/sync_debug.c:sync_debugfs_init
  - drivers/usb/common/common.c:usb_common_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_root
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/opp/debugfs.c:opp_debug_init
  - drivers/opp/debugfs.c:opp_debug_register
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_init_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/ras/debugfs.c:ras_debugfs_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8143d504-ffffffff8143d523: debugfs_create_dir.cold (STB_LOCAL)
ffffffff8143d070-ffffffff8143d166: debugfs_create_dir (STB_GLOBAL)
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
