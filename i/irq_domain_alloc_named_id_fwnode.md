# Function: <code>irq_domain_alloc_named_id_fwnode</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058cd5)
Location: include/linux/irqdomain.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b27c)
Location: include/linux/irqdomain.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ca036)
Location: include/linux/irqdomain.h:228
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c5f)
Location: include/linux/irqdomain.h:228
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d1b5)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f78c)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff81630a06)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ca0f)
Location: include/linux/irqdomain.h:235
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81060175)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106289c)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166b465)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e58)
Location: include/linux/irqdomain.h:235
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81065ee5)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106859c)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff81689b75)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f38)
Location: include/linux/irqdomain.h:237
Inline: True
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106969e)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bd99)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c1155)
Location: include/linux/irqdomain.h:238
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf8a3)
Location: include/linux/irqdomain.h:238
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828feec1)
Location: include/linux/irqdomain.h:238
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a01e)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c949)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e41b5)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f36e3)
Location: include/linux/irqdomain.h:245
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82908064)
Location: include/linux/irqdomain.h:245
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81070c85)
Location: include/linux/irqdomain.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073c99)
Location: include/linux/irqdomain.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179a465)
Location: include/linux/irqdomain.h:246
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab983)
Location: include/linux/irqdomain.h:246
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82d1e829)
Location: include/linux/irqdomain.h:246
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107205d)
Location: include/linux/irqdomain.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8107475d)
Location: include/linux/irqdomain.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff81bd7eca)
Location: include/linux/irqdomain.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_create_irq_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8b65)
Location: include/linux/irqdomain.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7d63)
Location: include/linux/irqdomain.h:247
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8300c637)
Location: include/linux/irqdomain.h:247
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072b71)
Location: include/linux/irqdomain.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8107520d)
Location: include/linux/irqdomain.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff831da370)
Location: include/linux/irqdomain.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178a905)
Location: include/linux/irqdomain.h:243
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179aed2)
Location: include/linux/irqdomain.h:243
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83217421)
Location: include/linux/irqdomain.h:243
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107ea8e)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810826fd)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd46d)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff81811be5)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823a02)
Location: include/linux/irqdomain.h:242
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83300dff)
Location: include/linux/irqdomain.h:242
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e3f0)
Location: include/linux/irqdomain.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810922dd)
Location: include/linux/irqdomain.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In arch/x86/kernel/hpet.c (ffffffff8346ee5c)
Location: include/linux/irqdomain.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff819529e5)
Location: include/linux/irqdomain.h:256
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962e6f)
Location: include/linux/irqdomain.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff834b9b47)
Location: include/linux/irqdomain.h:256
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a2b90)
Location: include/linux/irqdomain.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/hpet.c (ffffffff83e95468)
Location: include/linux/irqdomain.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab7e75)
Location: include/linux/irqdomain.h:244
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbee0)
Location: include/linux/irqdomain.h:244
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83ef6eb1)
Location: include/linux/irqdomain.h:244
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5c36)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/hpet.c (ffffffff836b8fc8)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b041b5)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18a60)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8371c961)
Location: include/linux/irqdomain.h:248
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810acbe6)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/hpet.c (ffffffff838e98a7)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57db5)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e3cf)
Location: include/linux/irqdomain.h:248
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83950481)
Location: include/linux/irqdomain.h:248
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v4.c (ffff8000106751a4)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v4.c (c081d568)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
</details>
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069b0e)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c439)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a9c95)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8ed3)
Location: include/linux/irqdomain.h:245
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828ef835)
Location: include/linux/irqdomain.h:245
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059e6e)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c759)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816875f5)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696b13)
Location: include/linux/irqdomain.h:245
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828e6cd8)
Location: include/linux/irqdomain.h:245
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069fbe)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c8e9)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d7e75)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e73a3)
Location: include/linux/irqdomain.h:245
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82903387)
Location: include/linux/irqdomain.h:245
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b73e)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106dfe9)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f2425)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701aa3)
Location: include/linux/irqdomain.h:245
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff829090c6)
Location: include/linux/irqdomain.h:245
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
</details>
</li>
</ul>

## Differences
