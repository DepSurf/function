# Function: <code>x2apic_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f7114c)
Location: arch/x86/include/asm/apic.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f71ff5)
Location: arch/x86/include/asm/apic.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81058531)
Location: arch/x86/include/asm/apic.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105996d)
Location: arch/x86/include/asm/apic.h:235
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f5c)
Location: arch/x86/include/asm/apic.h:235
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153dd5e)
Location: arch/x86/include/asm/apic.h:235
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a204)
Location: arch/x86/include/asm/apic.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a743)
Location: arch/x86/include/asm/apic.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81058861)
Location: arch/x86/include/asm/apic.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059bed)
Location: arch/x86/include/asm/apic.h:242
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a22c)
Location: arch/x86/include/asm/apic.h:242
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592d32)
Location: arch/x86/include/asm/apic.h:242
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd56d5)
Location: arch/x86/include/asm/apic.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5c0a)
Location: arch/x86/include/asm/apic.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b5f1)
Location: arch/x86/include/asm/apic.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c9ad)
Location: arch/x86/include/asm/apic.h:241
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf7c)
Location: arch/x86/include/asm/apic.h:241
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c05f2)
Location: arch/x86/include/asm/apic.h:241
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b5a39)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6a01)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105ad41)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c0bd)
Location: arch/x86/include/asm/apic.h:240
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c3ed)
Location: arch/x86/include/asm/apic.h:240
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d60d1)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bc394)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd322)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f281)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ff7d)
Location: arch/x86/include/asm/apic.h:256
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106055d)
Location: arch/x86/include/asm/apic.h:256
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ce81)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e6141)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e726e)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81062391)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106314d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106363d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e92d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8167828a)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289cc84)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289ddb7)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81068091)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068d4d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106933d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107494d)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8169736a)
Location: arch/x86/include/asm/apic.h:257
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b4f6d)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5c4f)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b881)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c56e)
Location: arch/x86/include/asm/apic.h:259
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cb8d)
Location: arch/x86/include/asm/apic.h:259
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828b8f33)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c19d5)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfccd)
Location: arch/x86/include/asm/apic.h:259
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff828a93f9)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b83ca)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9113)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c341)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dc6e)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e2ed)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828bf421)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e48f5)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3b0d)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8102f7f4-ffffffff8102f844: x2apic_enabled.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031f14)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e00f)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cde119)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8107365c)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81080912)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd/init.c (ffffffff8179b163)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
**Symbols:**

```
ffffffff81031f14-ffffffff81031f74: x2apic_enabled (STB_LOCAL)
ffffffff8106e00f-ffffffff8106e06f: x2apic_enabled (STB_LOCAL)
ffffffff81080912-ffffffff81080972: x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81bd2f33)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6d77)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca4d7)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bd81eb)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
**Symbols:**

```
ffffffff81bd2f33-ffffffff81bd2f93: x2apic_enabled (STB_LOCAL)
ffffffff81bd6d77-ffffffff81bd6dd7: x2apic_enabled (STB_LOCAL)
ffffffff81bd81eb-ffffffff81bd824b: x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81bc530f)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bc8e7a)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4dfc)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d9752)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bca025)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b943)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81bc530f-ffffffff81bc536f: x2apic_enabled (STB_LOCAL)
ffffffff81bc8e7a-ffffffff81bc8eda: x2apic_enabled (STB_LOCAL)
ffffffff81bca025-ffffffff81bca085: x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81c97edf)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c9d8ce)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7967)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc071)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81c9f334)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81824553)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81c97edf-ffffffff81c97f3f: x2apic_enabled (STB_LOCAL)
ffffffff81c9d8ce-ffffffff81c9d92e: x2apic_enabled (STB_LOCAL)
ffffffff81c9f334-ffffffff81c9f394: x2apic_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int x2apic_enabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81e4735c)
Location: arch/x86/include/asm/apic.h:256
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cd79)
Location: arch/x86/include/asm/apic.h:256
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff834695de)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346d9af)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81e4ea70)
Location: arch/x86/include/asm/apic.h:256
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8196430e)
Location: arch/x86/include/asm/apic.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81e4735c-ffffffff81e473d1: x2apic_enabled (STB_LOCAL)
ffffffff81e4cd79-ffffffff81e4cdee: x2apic_enabled (STB_LOCAL)
ffffffff81e4ea70-ffffffff81e4eae5: x2apic_enabled (STB_LOCAL)
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
In arch/x86/hyperv/hv_apic.c (ffffffff83e72c6f)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e009)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e9141e)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff83e9750e)
Location: arch/x86/include/asm/apic.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd39c)
Location: arch/x86/include/asm/apic.h:253
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
In arch/x86/hyperv/hv_apic.c (ffffffff83693c1f)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b18a9)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b5c9f)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff836bb0be)
Location: arch/x86/include/asm/apic.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19f0c)
Location: arch/x86/include/asm/apic.h:255
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
In arch/x86/hyperv/hv_apic.c (ffffffff838c39ac)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1df1)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e582b)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff838ebaac)
Location: arch/x86/include/asm/apic.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/apic.h:231
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff82897409)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a63d1)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a711a)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106be31)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc0e)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d28d)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828aa3f7)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa3d5)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b92fd)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8102f954-ffffffff8102f9a4: x2apic_enabled.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8288f722)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e4f2)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f211)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c142)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cf15)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d765)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828a25f1)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81688353)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f15)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8101f329-ffffffff8101f374: x2apic_enabled.part.0 (STB_LOCAL)
ffffffff810572bd-ffffffff81057308: x2apic_enabled.part.0 (STB_LOCAL)
ffffffff81067d9e-ffffffff81067de9: x2apic_enabled.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff828aa3f9)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b92e1)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba02a)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c2e1)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d0be)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d73d)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828bd2f6)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d85b5)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e77cd)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8102f7b4-ffffffff8102f804: x2apic_enabled.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff828aa409)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b93e2)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba140)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106d9e1)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f33e)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f9bd)
Location: arch/x86/include/asm/apic.h:264
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828c0443)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2b65)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701ecd)
Location: arch/x86/include/asm/apic.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81030604-ffffffff81030654: x2apic_enabled.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
