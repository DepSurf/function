# Function: <code>register_syscore_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8154c1d0)
Location: drivers/base/syscore.c:22
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/processor_idle.c:acpi_processor_syscore_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff8154c1d0-ffffffff8154c214: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8159dfc0)
Location: drivers/base/syscore.c:22
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_syscore_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff8159dfc0-ffffffff8159e004: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815cc570)
Location: drivers/base/syscore.c:22
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_syscore_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff815cc570-ffffffff815cc5b4: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815e1120)
Location: drivers/base/syscore.c:22
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff815e1120-ffffffff815e1164: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81648240)
Location: drivers/base/syscore.c:22
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81648240-ffffffff81648284: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81683810)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81683810-ffffffff81683854: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816a34e0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/common.c:init_cpu_syscore
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff816a34e0-ffffffff816a3524: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816dc3f0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff816dc3f0-ffffffff816dc434: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81700480)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81700480-ffffffff817004c4: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817ba3c0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff817ba3c0-ffffffff817ba407: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817cf0d0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff817cf0d0-ffffffff817cf117: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817b2ae0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff817b2ae0-ffffffff817b2b27: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8183bf80)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff8183bf80-ffffffff8183bfc7: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8197e710)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff8197e710-ffffffff8197e75f: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81aebcc0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81aebcc0-ffffffff81aebd0f: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81b39f00)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81b39f00-ffffffff81b39f4f: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81b919c0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81b919c0-ffffffff81b91a0f: register_syscore_ops (STB_GLOBAL)
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
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffff8000108eb730)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - kernel/time/sched_clock.c:sched_clock_syscore_init
  - kernel/cpu_pm.c:cpu_pm_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/gpio/gpio-mxc.c:gpio_mxc_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_probe
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffff8000108eb730-ffff8000108eb780: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c09d9740)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - kernel/time/sched_clock.c:sched_clock_syscore_init
  - kernel/cpu_pm.c:cpu_pm_init
  - drivers/irqchip/exynos-combiner.c:combiner_of_init
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/gpio/gpio-mxc.c:gpio_mxc_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_setup
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/clk/samsung/clk.c:samsung_clk_extended_sleep_init
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
```
**Symbols:**

```
c09d9740-c09d9788: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c000000000982db0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init_sys
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
c000000000982db0-c000000000982e2c: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffe00057f2bc)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - kernel/time/sched_clock.c:sched_clock_syscore_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffe00057f2bc-ffffffe00057f312: register_syscore_ops (STB_GLOBAL)
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
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816c5c70)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/xen/suspend.c:xen_setup_syscore_ops
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff816c5c70-ffffffff816c5cb4: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816a0ef0)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff816a0ef0-ffffffff816a0f34: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816f4140)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff816f4140-ffffffff816f4184: register_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8170e970)
Location: drivers/base/syscore.c:21
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/i8259.c:i8259A_init_ops
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/apic.c:init_lapic_sysfs
  - arch/x86/kernel/apic/io_apic.c:ioapic_init_ops
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - kernel/irq/generic-chip.c:irq_gc_init_ops
  - kernel/irq/pm.c:irq_pm_init_ops
  - kernel/time/timekeeping.c:timekeeping_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff8170e970-ffffffff8170e9b4: register_syscore_ops (STB_GLOBAL)
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
