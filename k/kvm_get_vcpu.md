# Function: <code>kvm_get_vcpu</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b51dc)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:vcpu_stat_get_per_vm
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_on_spin
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arm.c (ffff8000100c7cf0)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_mpidr_to_vcpu
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_arm_resume_guest
  - virt/kvm/arm/arm.c:kvm_arm_halt_guest
```
```
In virt/kvm/arm/psci.c (ffff8000100ce394)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd4b4)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:vgic_kick_vcpus
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100dd9ec)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e0084)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0838)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e38b4)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4e38)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_set_redist_base
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_set_redist_base
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e6554)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v3_parse_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:lock_all_vcpus
  - virt/kvm/arm/vgic/vgic-kvm-device.c:unlock_vcpus
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e8d18)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_ite
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_cmd_handle_mapi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
```
```
In virt/kvm/arm/vgic/vgic-debug.c (ffff8000100eb654)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ee038)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_timer_enable
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef5ac)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123794)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124ed4)
Location: include/linux/kvm_host.h:539
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_ipoll
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
