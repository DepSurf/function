# Function: <code>kasprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff813f8cd0)
Location: lib/kasprintf.c:50
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_alloc_fwnode
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:create_kmalloc_caches
  - security/keys/keyctl.c:keyctl_describe_key
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff813f8cd0-ffffffff813f8d35: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8143fc10)
Location: lib/kasprintf.c:52
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - security/keys/keyctl.c:keyctl_describe_key
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/power_supply_leds.c:power_supply_create_triggers
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff8143fc10-ffffffff8143fc75: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8145cd10)
Location: lib/kasprintf.c:52
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - security/keys/keyctl.c:keyctl_describe_key
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff8145cd10-ffffffff8145cd75: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81461f60)
Location: lib/kasprintf.c:52
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - security/keys/keyctl.c:keyctl_describe_key
  - security/security.c:security_getprocattr
  - security/security.c:security_add_hooks
  - security/selinux/hooks.c:selinux_getprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/lsm.c:apparmor_getprocattr
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81461f60-ffffffff81461fc5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8148de40)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - security/keys/keyctl.c:keyctl_describe_key
  - security/security.c:security_add_hooks
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff8148de40-ffffffff8148dea5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814c2bc0)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/security.c:security_add_hooks
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/ipmi/ipmi_dmi.c:dmi_add_platform_ipmi
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff814c2bc0-ffffffff814c2c25: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814d7270)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/security.c:security_add_hooks
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff814d7270-ffffffff814d72d5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815030d0)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/security.c:security_add_hooks
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff815030d0-ffffffff81503135: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81521070)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81521070-ffffffff815210d5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81584270)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:memcg_create_kmem_cache
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81584270-ffffffff815842d5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a1380)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_bat_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff815a1380-ffffffff815a13e5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a8230)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff815a8230-ffffffff815a8295: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff816111f0)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/msi.c:msi_populate_sysfs
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - lib/bitmap.c:bitmap_print_to_buf
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff816111f0-ffffffff81611255: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff816dd220)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/msi.c:msi_sysfs_populate_desc
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - lib/bitmap.c:bitmap_print_to_buf
  - lib/string_helpers.c:kasprintf_strarray
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff816dd220-ffffffff816dd29f: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff817cd090)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/msi.c:msi_sysfs_populate_desc
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - lib/bitmap.c:bitmap_print_to_buf
  - lib/string_helpers.c:kasprintf_strarray
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff817cd090-ffffffff817cd10f: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8180b4a0)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/msi.c:msi_sysfs_populate_desc
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - lib/bitmap.c:bitmap_print_to_buf
  - lib/string_helpers.c:kasprintf_strarray
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_alloc_muex
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff8180b4a0-ffffffff8180b51f: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81851c80)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/msi.c:msi_sysfs_populate_desc
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/fs_context.c:logfc
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - lib/bitmap-str.c:bitmap_print_to_buf
  - lib/string_helpers.c:kasprintf_strarray
  - drivers/pinctrl/core.c:pinctrl_register_pins
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_alloc_device
  - drivers/iommu/iommu.c:iommu_group_alloc_device
  - drivers/base/dd.c:device_set_deferred_probe_reason
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/dma-buf/dma-heap.c:dma_heap_devnode
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_drv.c:drm_dev_register
  - drivers/gpu/drm/drm_encoder.c:__drm_encoder_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
  - drivers/gpu/drm/drm_sysfs.c:drm_devnode
  - drivers/gpu/drm/drm_pci.c:drm_pci_set_busid
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_add
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_crtc_add
  - drivers/accel/drm_accel.c:accel_devnode
  - drivers/net/phy/phy_device.c:phy_attached_print
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_alloc_muex
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/powercap/powercap_sys.c:seed_constraint_attributes
  - drivers/interconnect/core.c:icc_get
  - drivers/hte/hte.c:__hte_req_ts
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81851c80-ffffffff81851cff: kasprintf (STB_GLOBAL)
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
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffff80001062a700)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_parse_madt
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_parse_madt
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_get_phys
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_reserve_range
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
  - drivers/clk/zynqmp/clkc.c:zynqmp_register_clocks
  - drivers/clk/zynqmp/clkc.c:zynqmp_register_clocks
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_dma_init_virtual_channels
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/kobj.c:safe_name
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffff80001062a700-ffff80001062a778: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c07d18e4)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:init_machine_late
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_device
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_device
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_device
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - arch/arm/mach-imx/cpu.c:imx_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_get_phys
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_clkctrl_clk_register
  - drivers/clk/ti/clkctrl.c:_ti_clkctrl_clk_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_dma_init_virtual_channels
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/samsung/exynos-chipid.c:exynos_chipid_early_init
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_soc_device_register
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_soc_device_register
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_soc_device_register
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/kobj.c:safe_name
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - sound/sound_core.c:sound_devnode
  - sound/soc/soc-core.c:snd_soc_cnew
  - sound/soc/soc-core.c:soc_probe_component
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/soc-dapm.c:dapm_create_or_share_kcontrol
  - sound/soc/soc-component.c:snd_soc_component_force_enable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_force_enable_pin
  - sound/soc/soc-component.c:snd_soc_component_get_pin_status
  - sound/soc/soc-component.c:snd_soc_component_nc_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_nc_pin
  - sound/soc/soc-component.c:snd_soc_component_disable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_disable_pin
  - sound/soc/soc-component.c:snd_soc_component_enable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_enable_pin
  - sound/soc/soc-pcm.c:dpcm_add_paths
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
c07d18e4-c07d1940: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c0000000007cc710)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_register_group
  - arch/powerpc/mm/init-common.c:pgtable_cache_add
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/hv-24x7.c:device_str_attr_create
  - arch/powerpc/perf/hv-24x7.c:device_str_attr_create
  - arch/powerpc/perf/hv-24x7.c:device_str_attr_create
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:new_kmalloc_cache
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/kobj.c:safe_name
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
c0000000007cc710-c0000000007cc754: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffe00045b08a)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - mm/slab_common.c:new_kmalloc_cache
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/kobj.c:safe_name
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffe00045b08a-ffffffe00045b0b8: kasprintf (STB_GLOBAL)
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
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81519650)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/nvme/host/core.c:nvme_async_event_work
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81519650-ffffffff815196b5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81509940)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/nvme/host/core.c:nvme_async_event_work
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff81509940-ffffffff815099a5: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815156e0)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff815156e0-ffffffff81515745: kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kasprintf(gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8152ee70)
Location: lib/kasprintf.c:53
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_devnode
  - arch/x86/platform/uv/tlb_uv.c:tunables_read
  - kernel/irq/irqdomain.c:irq_domain_update_bus_token
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - mm/slab_common.c:kmalloc_cache_name
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/cma.c:cma_init_reserved_mem
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - block/bsg.c:bsg_devnode
  - drivers/pinctrl/pinmux.c:pinmux_request_gpio
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_xs.c:join
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_add_driver
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/vfio/vfio.c:vfio_devnode
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/usb.c:usb_devnode
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_devnode
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/power/supply/power_supply_leds.c:power_supply_create_triggers
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - drivers/powercap/powercap_sys.c:powercap_init
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
```
**Symbols:**

```
ffffffff8152ee70-ffffffff8152eed5: kasprintf (STB_GLOBAL)
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
