# Function: <code>hypervisor_is_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/hypervisor.h:58
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81043a45)
Location: arch/x86/include/asm/hypervisor.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/mm/pti.c (ffffffff826ef6ca)
Location: arch/x86/include/asm/hypervisor.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81045325)
Location: arch/x86/include/asm/hypervisor.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/mm/pti.c (ffffffff828a63b8)
Location: arch/x86/include/asm/hypervisor.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810474e9)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828be9d6)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828fee9e)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c67)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c4e78)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82908041)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c2d9)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/mm/pti.c (ffffffff82ce8284)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82d1e806)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b7f9)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/mm/pti.c (ffffffff82fd5ca3)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8300c602)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d4a7)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/mm/pti.c (ffffffff831e05bd)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff832173bb)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8105427f)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff832c3c81)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83300d7d)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/hyperv/ivm.c (ffffffff8103f20e)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060993)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff834649fb)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:init_s4_sigcheck
```
```
In arch/x86/mm/pti.c (ffffffff8347658f)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff834b9ac5)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/hyperv/ivm.c (ffffffff8104833e)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f266)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff83e87a3a)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:init_s4_sigcheck
```
```
In arch/x86/mm/pti.c (ffffffff83e9f678)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83ef6e45)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/hyperv/ivm.c (ffffffff810486ee)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070b08)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff836aafda)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:init_s4_sigcheck
```
```
In arch/x86/mm/pti.c (ffffffff836c37f8)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8371c8f5)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/hyperv/ivm.c (ffffffff8104f7de)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078426)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_meltdown
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff838db76a)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:init_s4_sigcheck
```
```
In arch/x86/mm/pti.c (ffffffff838f4465)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83950415)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047dd7)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828afe10)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828ef812)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810370e7)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828a8002)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828e6cb5)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047c17)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c2d0f)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82903364)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049027)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c5e98)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff829090a3)
Location: arch/x86/include/asm/hypervisor.h:72
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
</details>
</li>
</ul>

## Differences
