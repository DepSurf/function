# Function: <code>register_reboot_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a2820)
Location: kernel/reboot.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff810a2820-ffffffff810a283a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a5f30)
Location: kernel/reboot.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810a5f30-ffffffff810a5f4a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810abb90)
Location: kernel/reboot.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810abb90-ffffffff810abbaa: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a8760)
Location: kernel/reboot.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810a8760-ffffffff810a877a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810aef86)
Location: kernel/reboot.c:86
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810aef10-ffffffff810aef2a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b5dd3)
Location: kernel/reboot.c:86
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810b5d50-ffffffff810b5d6a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf063)
Location: kernel/reboot.c:87
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810befe0-ffffffff810beffa: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c5173)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810c50f0-ffffffff810c510a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce273)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810ce1f0-ffffffff810ce20a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d8043)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810d7fc0-ffffffff810d7fda: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d2ea3)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810d2e20-ffffffff810d2e3a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d4ba3)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810d4b20-ffffffff810d4b3a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810e7d6a)
Location: kernel/reboot.c:90
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810e7ce0-ffffffff810e7cfa: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811020ea)
Location: kernel/reboot.c:99
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff81102040-ffffffff81102062: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8112737a)
Location: kernel/reboot.c:99
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff811272b0-ffffffff811272d2: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113481a)
Location: kernel/reboot.c:99
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff81134750-ffffffff81134772: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113f80a)
Location: kernel/reboot.c:109
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/efi.c:register_update_efi_random_seed
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff8113f740-ffffffff8113f762: register_reboot_notifier (STB_GLOBAL)
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
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012dc20)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/events/core.c:perf_event_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/arm_sdei.c:sdei_probe
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffff80001012db70-ffff80001012dba4: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037dab0)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mtd/mtdcore.c:mtd_device_parse_register
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
c037da24-c037da4c: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176aa8)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/events/core.c:perf_event_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
**Symbols:**

```
c000000000176980-c0000000001769c0: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1ce4)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - kernel/events/core.c:perf_event_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffe0000e1c44-ffffffe0000e1c76: register_reboot_notifier (STB_GLOBAL)
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
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c85f3)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810c8570-ffffffff810c858a: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6e13)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810b6d90-ffffffff810b6daa: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7b23)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810c7aa0-ffffffff810c7aba: register_reboot_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int register_reboot_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d0013)
Location: kernel/reboot.c:89
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/events/core.c:perf_event_init
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/xen/manage.c:xen_setup_shutdown_event
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/md/md.c:md_init
  - drivers/firmware/efi/capsule.c:capsule_reboot_register
```
**Symbols:**

```
ffffffff810cff90-ffffffff810cffaa: register_reboot_notifier (STB_GLOBAL)
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
