# Function: <code>blocking_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a18e0)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - kernel/reboot.c:unregister_reboot_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a18e0-ffffffff810a199f: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a5000)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - kernel/reboot.c:unregister_reboot_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a5000-ffffffff810a50bf: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aac60)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - kernel/reboot.c:unregister_reboot_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_global_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
```
**Symbols:**

```
ffffffff810aac60-ffffffff810aad1f: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7760)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:unregister_reboot_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a7760-ffffffff810a781c: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adee0)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
```
**Symbols:**

```
ffffffff810adee0-ffffffff810adf9c: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4d50)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
```
**Symbols:**

```
ffffffff810b4d50-ffffffff810b4e0a: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdea0)
Location: kernel/notifier.c:266
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810bdea0-ffffffff810bdf5a: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3f70)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c3f70-ffffffff810c401b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cd080)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810cd080-ffffffff810cd12b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6ab0)
Location: kernel/notifier.c:233
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d6ab0-ffffffff810d6b5b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d15b0)
Location: kernel/notifier.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d15b0-ffffffff810d165b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3190)
Location: kernel/notifier.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d3190-ffffffff810d323b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6190)
Location: kernel/notifier.c:251
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810e6190-ffffffff810e623b: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100030)
Location: kernel/notifier.c:315
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module/main.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/char/random.c:unregister_random_vmfork_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff81100030-ffffffff811000e0: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81124eb0)
Location: kernel/notifier.c:315
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module/main.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/char/random.c:unregister_random_vmfork_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff81124eb0-ffffffff81124f60: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132c90)
Location: kernel/notifier.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module/main.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/char/random.c:unregister_random_vmfork_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff81132c90-ffffffff81132cf4: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113dba0)
Location: kernel/notifier.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - kernel/reboot.c:unregister_sys_off_handler
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module/main.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - mm/memory-tiers.c:unregister_mt_adistance_algorithm
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_unregister_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/char/random.c:unregister_random_vmfork_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/power/supply/power_supply_core.c:power_supply_unreg_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/platform/x86/amd/wbrf.c:amd_wbrf_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff8113dba0-ffffffff8113dc04: blocking_notifier_chain_unregister (STB_GLOBAL)
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bed8)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_unregister
  - drivers/of/overlay.c:of_overlay_notifier_unregister
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffff80001012bed8-ffff80001012bfb0: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c3f8)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_unregister_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_unregister
  - drivers/of/overlay.c:of_overlay_notifier_unregister
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - sound/soc/soc-jack.c:snd_soc_jack_notifier_unregister
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
c037c3f8-c037c4dc: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174cd0)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - kernel/reboot.c:devm_unregister_reboot_notifier
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_unregister
  - drivers/of/overlay.c:of_overlay_notifier_unregister
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
c000000000174cd0-c000000000174e08: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0bd0)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_unregister
  - drivers/of/overlay.c:of_overlay_notifier_unregister
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffe0000e0bd0-ffffffe0000e0c74: blocking_notifier_chain_unregister (STB_GLOBAL)
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
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7400)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c7400-ffffffff810c74ab: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5c20)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810b5c20-ffffffff810b5ccb: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6950)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c6950-ffffffff810c69fb: blocking_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_unregister(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cee10)
Location: kernel/notifier.c:268
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_unregister_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
  - kernel/power/qos.c:pm_qos_remove_notifier
  - kernel/power/main.c:unregister_pm_notifier
  - kernel/module.c:unregister_module_notifier
  - kernel/tracepoint.c:unregister_tracepoint_module_notifier
  - kernel/padata.c:padata_unregister_cpumask_notifier
  - mm/oom_kill.c:unregister_oom_notifier
  - mm/vmalloc.c:unregister_vmap_purge_notifier
  - security/security.c:unregister_blocking_lsm_notifier
  - crypto/algapi.c:crypto_unregister_notifier
  - drivers/video/backlight/backlight.c:backlight_unregister_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_unregister_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_unregister
  - drivers/acpi/event.c:unregister_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_unregister
  - drivers/acpi/hed.c:unregister_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:unregister_xenstore_notifier
  - drivers/regulator/core.c:regulator_unregister_notifier
  - drivers/iommu/iommu.c:iommu_group_unregister_notifier
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/memory.c:unregister_memory_notifier
  - drivers/mfd/da903x.c:da903x_unregister_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_unregister
  - drivers/mfd/adp5520.c:adp5520_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unregister_notifier
  - drivers/usb/core/notify.c:usb_unregister_notify
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/nvmem/core.c:nvmem_unregister_notifier
  - net/netlink/af_netlink.c:netlink_unregister_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_validator_notifier
  - net/ipv4/devinet.c:unregister_inetaddr_notifier
  - net/ipv6/addrconf_core.c:unregister_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810cee10-ffffffff810ceebb: blocking_notifier_chain_unregister (STB_GLOBAL)
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
