# Function: <code>kvm_para_has_feature</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063fe3)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81f74713)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff81063c03)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81f9cf25)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff810670ba)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81fd84b4)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff8106638a)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff820b92c8)
Location: include/linux/kvm_para.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff8106a58a)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/kvmclock.c (ffffffff826bfbef)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff826e99b9)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff826e9aea)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828a0604)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a07ed)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828b87e0)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828b89d3)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828becce)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828beec1)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff82ce2feb)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82ce31b1)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff82fd02dd)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82fd04aa)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff831dad91)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff831db13d)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff832be040)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:pv_ipi_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff832be4b2)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff8346ff05)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_suspend
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:pv_ipi_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff834701c6)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff83e96858)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_suspend
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96c8d)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff836ba3e1)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_suspend
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba83d)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff838ead51)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:kvm_msi_ext_dest_id
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_suspend
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb23d)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kvm.c (c000000001353db0)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
```
</details>
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
In arch/x86/kernel/kvm.c (ffffffff828a9ca4)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a9e97)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828a1db5)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a2178)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828bcba3)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bcd96)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
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
In arch/x86/kernel/kvm.c (ffffffff828bfcfb)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bfeee)
Location: include/linux/kvm_para.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
</details>
</li>
</ul>

## Differences
