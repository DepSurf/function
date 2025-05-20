# Function: <code>strcspn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1b70)
Location: lib/string.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff813f1b70-ffffffff813f1bb6: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438510)
Location: lib/string.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff81438510-ffffffff81438556: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455500)
Location: lib/string.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff81455500-ffffffff81455546: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6f70)
Location: lib/string.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff818f6f70-ffffffff818f6fb6: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d970)
Location: lib/string.c:539
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff8197d970-ffffffff8197d9b6: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9e70)
Location: lib/string.c:539
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:layout_and_allocate
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
```
**Symbols:**

```
ffffffff819d9e70-ffffffff819d9eb2: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12090)
Location: lib/string.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81a12090-ffffffff81a120d2: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81520)
Location: lib/string.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81a81520-ffffffff81a81563: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab85f0)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81ab85f0-ffffffff81ab8633: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3230)
Location: lib/string.c:625
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:blacklisted
  - kernel/hung_task.c:check_hung_task
  - lib/dump_stack.c:dump_stack_print_info
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
```
**Symbols:**

```
ffffffff815f3230-ffffffff815f3273: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff816178e0)
Location: lib/string.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:blacklisted
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:check_hung_task
  - lib/dump_stack.c:dump_stack_print_info
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff816178e0-ffffffff81617923: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815faf60)
Location: lib/string.c:622
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:check_hung_task
  - lib/dump_stack.c:dump_stack_print_info
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff815faf60-ffffffff815fafa3: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668810)
Location: lib/string.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/hung_task.c:check_hung_task
  - lib/dump_stack.c:dump_stack_print_info
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81668810-ffffffff81668853: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781f40)
Location: lib/string.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/module/main.c:load_module
  - kernel/module/version.c:same_magic
  - kernel/module/version.c:same_magic
  - kernel/hung_task.c:check_hung_task
  - lib/dump_stack.c:dump_stack_print_info
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
```
**Symbols:**

```
ffffffff81781f40-ffffffff81781fbc: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203ed40)
Location: lib/string.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/module/main.c:load_module
  - kernel/module/version.c:same_magic
  - kernel/module/version.c:same_magic
  - kernel/hung_task.c:check_hung_task
  - security/apparmor/lib.c:aa_parse_debug_params
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8203ed40-ffffffff8203edbc: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd250)
Location: lib/string.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/module/main.c:blacklisted
  - kernel/module/version.c:same_magic
  - kernel/module/version.c:same_magic
  - kernel/hung_task.c:check_hung_task
  - security/apparmor/lib.c:aa_parse_debug_params
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff820bd250-ffffffff820bd2cc: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197b50)
Location: lib/string.c:447
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/module/main.c:blacklisted
  - kernel/module/version.c:same_magic
  - kernel/module/version.c:same_magic
  - kernel/hung_task.c:check_hung_task
  - security/apparmor/lib.c:aa_parse_debug_params
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff82197b50-ffffffff82197bcc: strcspn (STB_GLOBAL)
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
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92a70)
Location: lib/string.c:584
Inline: False
Direct callers:
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffff800010d92a70-ffff800010d92ac0: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f200)
Location: lib/string.c:584
Inline: False
Direct callers:
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c0e8f200-c0e8f264: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6a00)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:iommu_setup
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c000000000ed6a00-c000000000ed6a60: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcb9c)
Location: lib/string.c:584
Inline: False
Direct callers:
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/of/base.c:__of_find_node_by_path
  - lib/dump_stack.c:dump_stack_print_info
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffffffe0008bcb9c-ffffffe0008bcbde: strcspn (STB_GLOBAL)
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
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57440)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81a57440-ffffffff81a57483: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14520)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81a14520-ffffffff81a14563: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3830)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81ac3830-ffffffff81ac3873: strcspn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char *s, const char *reject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfd00)
Location: lib/string.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - arch/x86/kernel/early_printk.c:early_serial_init
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
  - kernel/params.c:param_array_set
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/module.c:load_module
  - kernel/hung_task.c:watchdog
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/iommu/intel-iommu.c:intel_iommu_setup
  - drivers/iommu/irq_remapping.c:setup_irqremap
  - drivers/base/platform.c:early_platform_driver_register
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81acfd00-ffffffff81acfd43: strcspn (STB_GLOBAL)
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
