# Function: <code>blocking_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1840)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - kernel/reboot.c:register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_global_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - net/ipv4/devinet.c:register_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a1840-ffffffff810a18d6: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4f60)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - kernel/reboot.c:register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_global_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - net/ipv4/devinet.c:register_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a4f60-ffffffff810a4ff6: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aabc0)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - kernel/reboot.c:register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_global_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
```
**Symbols:**

```
ffffffff810aabc0-ffffffff810aac56: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a76c0)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
```
**Symbols:**

```
ffffffff810a76c0-ffffffff810a775b: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ade40)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
```
**Symbols:**

```
ffffffff810ade40-ffffffff810adedb: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4cb0)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
```
**Symbols:**

```
ffffffff810b4cb0-ffffffff810b4d4b: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bde00)
Location: kernel/notifier.c:213
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810bde00-ffffffff810bde9b: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3d70)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c3d70-ffffffff810c3dcf: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cce80)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810cce80-ffffffff810ccedf: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d69e0)
Location: kernel/notifier.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d69e0-ffffffff810d6a3f: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d14e0)
Location: kernel/notifier.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d14e0-ffffffff810d153f: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d30c0)
Location: kernel/notifier.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810d30c0-ffffffff810d311f: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e64e0)
Location: kernel/notifier.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810e64e0-ffffffff810e659b: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811002b0)
Location: kernel/notifier.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module/main.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/char/random.c:register_random_vmfork_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff811002b0-ffffffff81100324: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125170)
Location: kernel/notifier.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module/main.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/char/random.c:register_random_vmfork_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff81125170-ffffffff811251e4: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132da0)
Location: kernel/notifier.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module/main.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/char/random.c:register_random_vmfork_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff81132da0-ffffffff81132e0c: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113dcb0)
Location: kernel/notifier.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:register_sys_off_handler
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module/main.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - mm/memory-tiers.c:register_mt_adistance_algorithm
  - fs/efivarfs/super.c:efivarfs_fill_super
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/acpi/apei/ghes.c:ghes_register_vendor_record_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/char/random.c:register_random_vmfork_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/power/supply/power_supply_core.c:power_supply_reg_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/platform/x86/amd/wbrf.c:amd_wbrf_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff8113dcb0-ffffffff8113dd1c: blocking_notifier_chain_register (STB_GLOBAL)
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
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bc60)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_register
  - drivers/of/overlay.c:of_overlay_notifier_register
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffff80001012bc60-ffff80001012bce8: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c18c)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_register_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_register
  - drivers/of/overlay.c:of_overlay_notifier_register
  - drivers/nvmem/core.c:nvmem_register_notifier
  - sound/soc/soc-jack.c:snd_soc_jack_notifier_register
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
c037c18c-c037c1fc: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174970)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_register
  - drivers/of/overlay.c:of_overlay_notifier_register
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
c000000000174970-c000000000174a10: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0978)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/of/dynamic.c:of_reconfig_notifier_register
  - drivers/of/overlay.c:of_overlay_notifier_register
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffe0000e0978-ffffffe0000e09f4: blocking_notifier_chain_register (STB_GLOBAL)
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
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7200)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c7200-ffffffff810c725f: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5a20)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810b5a20-ffffffff810b5a7f: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6750)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810c6750-ffffffff810c67af: blocking_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blocking_notifier_chain_register(struct blocking_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cec10)
Location: kernel/notifier.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_register_decode_chain
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_register_injector_chain
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_register_pmic_bus_access_notifier
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/power/qos.c:pm_qos_add_notifier
  - kernel/power/main.c:register_pm_notifier
  - kernel/module.c:register_module_notifier
  - kernel/tracepoint.c:register_tracepoint_module_notifier
  - kernel/padata.c:padata_register_cpumask_notifier
  - mm/oom_kill.c:register_oom_notifier
  - mm/vmalloc.c:register_vmap_purge_notifier
  - security/security.c:register_blocking_lsm_notifier
  - crypto/algapi.c:crypto_register_notifier
  - drivers/video/backlight/backlight.c:backlight_register_notifier
  - drivers/video/fbdev/core/fb_notify.c:fb_register_client
  - drivers/acpi/scan.c:acpi_reconfig_notifier_register
  - drivers/acpi/event.c:register_acpi_notifier
  - drivers/acpi/button.c:acpi_lid_notifier_register
  - drivers/acpi/hed.c:register_acpi_hed_notifier
  - drivers/xen/xenbus/xenbus_probe.c:register_xenstore_notifier
  - drivers/regulator/core.c:regulator_register_notifier
  - drivers/iommu/iommu.c:iommu_group_register_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/power/qos.c:dev_pm_qos_add_notifier
  - drivers/base/memory.c:register_memory_notifier
  - drivers/mfd/da903x.c:da903x_register_notifier
  - drivers/mfd/ab3100-core.c:ab3100_event_register
  - drivers/mfd/adp5520.c:adp5520_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_register_notifier
  - drivers/usb/core/notify.c:usb_register_notify
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/nvmem/core.c:nvmem_register_notifier
  - net/netlink/af_netlink.c:netlink_register_notifier
  - net/ipv4/devinet.c:register_inetaddr_validator_notifier
  - net/ipv4/devinet.c:register_inetaddr_notifier
  - net/ipv6/addrconf_core.c:register_inet6addr_validator_notifier
  - net/switchdev/switchdev.c:register_switchdev_blocking_notifier
```
**Symbols:**

```
ffffffff810cec10-ffffffff810cec6f: blocking_notifier_chain_register (STB_GLOBAL)
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
