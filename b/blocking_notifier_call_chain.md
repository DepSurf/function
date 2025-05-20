# Function: <code>blocking_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1760)
Location: kernel/notifier.c:325
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_power_off
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/profile.c:profile_task_exit
  - kernel/profile.c:profile_munmap
  - kernel/module.c:SyS_delete_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - crypto/algapi.c:crypto_register_template
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_unregister_template
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
```
**Symbols:**

```
ffffffff810a1760-ffffffff810a1778: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4e80)
Location: kernel/notifier.c:325
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_register_template
  - crypto/algapi.c:crypto_remove_alg
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff810a4e80-ffffffff810a4e98: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aaae0)
Location: kernel/notifier.c:325
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_register_template
  - crypto/algapi.c:crypto_remove_alg
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff810aaae0-ffffffff810aaaf8: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7a50)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_call_pmic_bus_access_notifier_chain
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_register_template
  - crypto/algapi.c:crypto_remove_alg
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff810a7a50-ffffffff810a7aac: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ae1d0)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_call_pmic_bus_access_notifier_chain
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_register_template
  - crypto/algapi.c:crypto_remove_alg
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
```
**Symbols:**

```
ffffffff810ae1d0-ffffffff810ae22c: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5040)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_call_pmic_bus_access_notifier_chain
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
```
**Symbols:**

```
ffffffff810b5040-ffffffff810b509c: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810be190)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810be190-ffffffff810be1ec: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c4190)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810c4190-ffffffff810c41f8: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cd2a0)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810cd2a0-ffffffff810cd308: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6f00)
Location: kernel/notifier.c:292
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/algapi.c:crypto_wait_for_test
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810d6f00-ffffffff810d6f8b: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1a40)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/algapi.c:crypto_wait_for_test
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810d1a40-ffffffff810d1acb: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3620)
Location: kernel/notifier.c:325
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/algapi.c:crypto_wait_for_test
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810d3620-ffffffff810d36ab: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e67b0)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - mm/oom_kill.c:out_of_memory
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/algapi.c:crypto_wait_for_test
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810e67b0-ffffffff810e683b: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100870)
Location: kernel/notifier.c:370
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_init_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - mm/oom_kill.c:out_of_memory
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - crypto/api.c:crypto_wait_for_test
  - crypto/api.c:crypto_wait_for_test
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_entry_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81100870-ffffffff81100902: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811257d0)
Location: kernel/notifier.c:370
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/reboot.c:kernel_restart
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_init_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - mm/oom_kill.c:out_of_memory
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - crypto/api.c:crypto_wait_for_test
  - crypto/algapi.c:crypto_alg_finish_registration
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_cell_entry_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff811257d0-ffffffff81125862: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811329a0)
Location: kernel/notifier.c:376
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/reboot.c:kernel_restart
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_init_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - mm/oom_kill.c:out_of_memory
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - crypto/api.c:crypto_wait_for_test
  - crypto/algapi.c:crypto_alg_finish_registration
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_set_config
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/base/bus.c:bus_notify
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff811329a0-ffffffff81132a07: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d8b0)
Location: kernel/notifier.c:376
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
  - kernel/reboot.c:kernel_restart
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/main.c:pm_notifier_call_chain
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:do_init_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - mm/oom_kill.c:out_of_memory
  - mm/vmalloc.c:alloc_vmap_area
  - mm/memory-tiers.c:mt_calc_adistance
  - security/security.c:call_blocking_lsm_notifier
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - crypto/api.c:crypto_wait_for_test
  - crypto/algapi.c:crypto_alg_finish_registration
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/core.c:_notifier_call_chain
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/base/bus.c:bus_notify
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
  - drivers/base/memory.c:memory_block_online
  - drivers/base/memory.c:memory_block_online
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_call_notifier_chain
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/firmware/efi/vars.c:efivars_register
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_bridge_port_replay
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff8113d8b0-ffffffff8113d917: blocking_notifier_call_chain (STB_GLOBAL)
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
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012c2b0)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__arm64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffff80001012c2b0-ffff80001012c338: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c694)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_activation_notify
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
  - drivers/of/overlay.c:overlay_notify
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
c037c694-c037c710: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000175080)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
c000000000175080-c000000000175120: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0de2)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_set_cpumask
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/of/dynamic.c:__of_changeset_entry_notify
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffe0000e0de2-ffffffe0000e0e52: blocking_notifier_call_chain (STB_GLOBAL)
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
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7620)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810c7620-ffffffff810c7688: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5e40)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810b5e40-ffffffff810b5ea8: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6b70)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810c6b70-ffffffff810c6bd8: blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cf030)
Location: kernel/notifier.c:327
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/profile.c:profile_munmap
  - kernel/profile.c:profile_task_exit
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/padata.c:padata_replace
  - mm/vmalloc.c:alloc_vmap_area
  - security/security.c:call_blocking_lsm_notifier
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/fbdev/core/fb_notify.c:fb_notifier_call_chain
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/event.c:acpi_notifier_call_chain
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/hed.c:acpi_hed_notify
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/regulator/core.c:regulator_notifier_call_chain
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_bound
  - drivers/base/memory.c:memory_notify
  - drivers/mfd/da903x.c:da903x_irq_work
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_group_set_kvm
  - drivers/usb/core/notify.c:usb_notify_remove_bus
  - drivers/usb/core/notify.c:usb_notify_add_bus
  - drivers/usb/core/notify.c:usb_notify_remove_device
  - drivers/usb/core/notify.c:usb_notify_add_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add_v1
  - drivers/opp/core.c:_opp_kref_release
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_cell_add
  - drivers/nvmem/core.c:nvmem_cell_drop
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv6/addrconf_core.c:inet6addr_validator_notifier_call_chain
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff810cf030-ffffffff810cf098: blocking_notifier_call_chain (STB_GLOBAL)
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
