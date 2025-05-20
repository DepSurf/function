# Function: <code>apic_is_x2apic_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107cea6)
Location: arch/x86/include/asm/apic.h:108
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f72003)
Location: arch/x86/include/asm/apic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72dd0)
Location: arch/x86/include/asm/apic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810585af)
Location: arch/x86/include/asm/apic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059995)
Location: arch/x86/include/asm/apic.h:108
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f7d)
Location: arch/x86/include/asm/apic.h:108
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153ddf1)
Location: arch/x86/include/asm/apic.h:108
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8107cea6-ffffffff8107cefd: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107e982)
Location: arch/x86/include/asm/apic.h:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a769)
Location: arch/x86/include/asm/apic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b5f8)
Location: arch/x86/include/asm/apic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810588de)
Location: arch/x86/include/asm/apic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059c15)
Location: arch/x86/include/asm/apic.h:113
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a24d)
Location: arch/x86/include/asm/apic.h:113
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592dc5)
Location: arch/x86/include/asm/apic.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8107e982-ffffffff8107e9d9: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81083019)
Location: arch/x86/include/asm/apic.h:112
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5c30)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6b41)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b66e)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c9d5)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf9d)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0685)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81083019-ffffffff81083070: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056f08)
Location: arch/x86/include/asm/apic.h:111
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6a27)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b784c)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105adc4)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c0e5)
Location: arch/x86/include/asm/apic.h:111
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c413)
Location: arch/x86/include/asm/apic.h:111
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d60df)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81056f08-ffffffff81056f5f: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105ab75)
Location: arch/x86/include/asm/apic.h:120
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd348)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826be1f7)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f2dd)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ffa5)
Location: arch/x86/include/asm/apic.h:120
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060583)
Location: arch/x86/include/asm/apic.h:120
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ce8f)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8105ab75-ffffffff8105abcc: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105d9a5)
Location: arch/x86/include/asm/apic.h:121
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e7294)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7fb9)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810623ed)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81063175)
Location: arch/x86/include/asm/apic.h:121
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063663)
Location: arch/x86/include/asm/apic.h:121
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e953)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8167830e)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8105d9a5-ffffffff8105d9fc: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81063635)
Location: arch/x86/include/asm/apic.h:121
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dddd)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289eb02)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810680ed)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068d75)
Location: arch/x86/include/asm/apic.h:121
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069363)
Location: arch/x86/include/asm/apic.h:121
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81074973)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816973ee)
Location: arch/x86/include/asm/apic.h:121
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81063635-ffffffff8106368c: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066cb5)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5c77)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b69f0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b8dd)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c599)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cbb3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078538)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1a46)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfd4d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81066cb5-ffffffff81066d06: apic_is_x2apic_enabled (STB_LOCAL)
ffffffff81078538-ffffffff81078589: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f810)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067325)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b913b)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9ec5)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c39e)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dc99)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e313)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81079588)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4966)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3b8d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81067325-ffffffff81067376: apic_is_x2apic_enabled (STB_LOCAL)
ffffffff81079588-ffffffff810795d9: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031f36)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e031)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cde141)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdf1a7)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810736b4)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075105)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075780)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81080934)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In drivers/iommu/amd/init.c (ffffffff8179b1d4)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817abb8a)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81bd2f55)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6d99)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca4ff)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb546)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075735)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075dc0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bd820d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7f6a)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81bc5331)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bc8e9c)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4e24)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5ddd)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d9766)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810761d5)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076840)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bca047)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b9ad)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81c97f01)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c9d8f0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b798c)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8a40)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc085)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810837d5)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083fb0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81c9f356)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818245bd)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81e47382)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:x2apic_enabled
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cd9f)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469603)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a7d9)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346d9c3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093703)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810940b3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81e4ea96)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:x2apic_enabled
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81964364)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff83e72cd9)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8ce95)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e3ac)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f81a)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e915d4)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8d23)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a96d3)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff83e97433)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd40a)
Location: arch/x86/include/asm/apic.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff83693c89)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0725)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1c4c)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b30c0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b5e1a)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abf53)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac8e3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff836bafe3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19f7a)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff838c3b6d)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e0e55)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e2006)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e39a0)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e599a)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2cb3)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3563)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff838eb9d3)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e6fc)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f970)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066e15)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a7142)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7edd)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106be8e)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc39)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d2b3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078588)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa446)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b937d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81066e15-ffffffff81066e66: apic_is_x2apic_enabled (STB_LOCAL)
ffffffff81078588-ffffffff810785d9: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f329)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810572bd)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f239)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ff97)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c18c)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cf35)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d776)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067d9e)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816883b2)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f95)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f7d0)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810672c5)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba052)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baddc)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c33e)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d0e9)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d763)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078538)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8626)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e784d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff810672c5-ffffffff81067316: apic_is_x2apic_enabled (STB_LOCAL)
ffffffff81078538-ffffffff81078589: apic_is_x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool apic_is_x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81030620)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810688a5)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba168)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baef2)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106da3e)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f369)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f9e3)
Location: arch/x86/include/asm/apic.h:122
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a638)
Location: arch/x86/include/asm/apic.h:122
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2bd6)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701f4d)
Location: arch/x86/include/asm/apic.h:122
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff810688a5-ffffffff810688f6: apic_is_x2apic_enabled (STB_LOCAL)
ffffffff8107a638-ffffffff8107a689: apic_is_x2apic_enabled (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
