# Function: <code>debugfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131dda0)
Location: fs/debugfs/inode.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/core.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register
  - mm/memory.c:fault_around_debugfs
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/file.c:debugfs_create_mode
  - fs/debugfs/file.c:debugfs_create_mode
  - fs/debugfs/file.c:debugfs_create_mode
  - fs/debugfs/file.c:debugfs_create_blob
  - fs/debugfs/file.c:debugfs_create_regset32
  - fs/debugfs/file.c:debugfs_create_u32_array
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/char/virtio_console.c:add_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/clk/clk.c:clk_debugfs_add_file
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
ffffffff8131dda0-ffffffff8131deab: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352a96)
Location: fs/debugfs/inode.c:360
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register
  - mm/memory.c:fault_around_debugfs
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debugfs_add_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
ffffffff81352a60-ffffffff81352a8b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368d46)
Location: fs/debugfs/inode.c:360
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register
  - mm/memory.c:fault_around_debugfs
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debugfs_add_file
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
ffffffff81368d10-ffffffff81368d3b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137d3d6)
Location: fs/debugfs/inode.c:394
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:debugfs_create_files
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debugfs_add_file
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:pm_genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8137d3a0-ffffffff8137d3cb: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a22e6)
Location: fs/debugfs/inode.c:397
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/panic.c:register_warn_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:debugfs_create_files
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debugfs_add_file
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813a22b0-ffffffff813a22db: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d1553)
Location: fs/debugfs/inode.c:420
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_debugfs_init
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/panic.c:register_warn_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:debugfs_create_files
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813d1510-ffffffff813d153b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813ebdf3)
Location: fs/debugfs/inode.c:421
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/panic.c:register_warn_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff813ebdb0-ffffffff813ebddb: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81417ee3)
Location: fs/debugfs/inode.c:434
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81417ea0-ffffffff81417ecb: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81431da3)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81431d60-ffffffff81431d8b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814816c3)
Location: fs/debugfs/inode.c:435
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81481680-ffffffff814816ab: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149f21a)
Location: fs/debugfs/inode.c:450
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/ras/cec.c:create_debugfs_nodes
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff8149f1d0-ffffffff8149f1fb: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a51fa)
Location: fs/debugfs/inode.c:454
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff814a51b0-ffffffff814a51db: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fd33a)
Location: fs/debugfs/inode.c:454
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slub.c:debugfs_slab_add
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff814fd2f0-ffffffff814fd31b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158db9a)
Location: fs/debugfs/inode.c:459
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:debugfs_slab_add
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff8158db40-ffffffff8158db7d: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816342ea)
Location: fs/debugfs/inode.c:482
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmscan.c:init_lru_gen
  - mm/vmscan.c:init_lru_gen
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:debugfs_slab_add
  - mm/slub.c:debugfs_slab_add
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/kfence/core.c:kfence_debugfs_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff81634280-ffffffff816342bd: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166c5e5)
Location: fs/debugfs/inode.c:482
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmscan.c:init_lru_gen
  - mm/vmscan.c:init_lru_gen
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:debugfs_slab_add
  - mm/slub.c:debugfs_slab_add
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/power/domain.c:genpd_debug_add
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff8166c590-ffffffff8166c5cd: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a6e65)
Location: fs/debugfs/inode.c:489
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/power/main.c:pm_debugfs_init
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmscan.c:init_lru_gen
  - mm/vmscan.c:init_lru_gen
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:debugfs_slab_add
  - mm/slub.c:debugfs_slab_add
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/clk/clk-fractional-divider.c:clk_fd_debug_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/pmdomain/core.c:genpd_debug_init
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/pmdomain/core.c:genpd_debug_add
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_register
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_create_files
  - drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add
  - drivers/gpu/drm/drm_debugfs_crc.c:drm_debugfs_crtc_crc_add
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_stream_files
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
  - drivers/interconnect/core.c:icc_init
  - drivers/interconnect/core.c:icc_init
```
**Symbols:**

```
ffffffff816a6e10-ffffffff816a6e4d: debugfs_create_file (STB_GLOBAL)
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
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010516b8c)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/memblock.c:memblock_init_debugfs
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_probe
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
ffff800010516ae0-ffff800010516b54: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d190c)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
  - arch/arm/mach-omap2/pm-debug.c:pwrdms_setup
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/backing-dev.c:bdi_register_va
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/memblock.c:memblock_init_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_debugfs_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/musb/musb_debugfs.c:musb_init_debugfs
  - drivers/usb/musb/musb_debugfs.c:musb_init_debugfs
  - drivers/usb/musb/musb_debugfs.c:musb_init_debugfs
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/firmware/tegra/bpmp-debugfs.c:bpmp_populate_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - sound/soc/soc-core.c:snd_soc_init
  - sound/soc/soc-core.c:snd_soc_init
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_widgets
  - sound/soc/soc-dapm.c:snd_soc_dapm_debugfs_init
  - sound/soc/soc-pcm.c:soc_dpcm_debugfs_add
  - sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_debugfs_create
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
**Symbols:**

```
c06d18ac-c06d18f4: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065fbd0)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/powerpc/kernel/setup_64.c:rfi_flush_debugfs_init
  - arch/powerpc/kernel/security.c:count_cache_flush_debugfs_init
  - arch/powerpc/kernel/security.c:stf_barrier_debugfs_init
  - arch/powerpc/kernel/security.c:barrier_nospec_debugfs_init
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/platforms/powernv/opal-lpc.c:opal_lpc_debugfs_create_type
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - arch/powerpc/platforms/powernv/memtrace.c:__machine_initcall_powernv_memtrace_init
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir
  - arch/powerpc/platforms/powernv/vas-debug.c:vas_window_init_dbgdir
  - arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vpa_debugfs_init
  - arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init
  - arch/powerpc/xmon/xmon.c:setup_xmon_dbgfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/memblock.c:memblock_init_debugfs
  - mm/memblock.c:memblock_init_debugfs
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
c00000000065fb70-c00000000065fbac: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe000380232)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/ras/debugfs.c:ras_add_daemon_trace
```
**Symbols:**

```
ffffffe0003801ac-ffffffe000380208: debugfs_create_file (STB_GLOBAL)
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
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8142a383)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8142a340-ffffffff8142a36b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8141ae03)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8141adc0-ffffffff8141adeb: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81426523)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff814264e0-ffffffff8142650b: debugfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143d3e3)
Location: fs/debugfs/inode.c:436
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/severity.c:severities_debugfs_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/tlb.c:create_tlb_single_page_flush_ceiling
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/debug.c:sched_init_debug
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/main.c:pm_debugfs_init
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/kprobes.c:debugfs_kprobe_init
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_create_buf_file_callback
  - mm/vmstat.c:extfrag_debug_init
  - mm/vmstat.c:extfrag_debug_init
  - mm/slab_common.c:memcg_slabinfo_init
  - mm/huge_memory.c:split_huge_pages_debugfs
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - fs/debugfs/file.c:debugfs_create_regset32
  - lib/error-inject.c:init_error_injection
  - lib/dynamic_debug.c:dynamic_debug_init_debugfs
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_init
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinmux.c:pinmux_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/pinctrl/pinconf.c:pinconf_init_device_debugfs
  - drivers/gpio/gpiolib.c:gpiolib_debugfs_init
  - drivers/pwm/core.c:pwm_debugfs_init
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_debug_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:regulator_init
  - drivers/regulator/core.c:create_regulator
  - drivers/char/virtio_console.c:add_port
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/power/wakeup.c:wakeup_sources_debugfs_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/power/domain.c:genpd_debug_init
  - drivers/base/regmap/regcache-rbtree.c:rbtree_debugfs_init
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_debug_dir
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_create_trace_file
  - drivers/ras/debugfs.c:ras_add_daemon_trace
  - drivers/ras/cec.c:cec_init
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8143d3a0-ffffffff8143d3cb: debugfs_create_file (STB_GLOBAL)
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
