# Function: <code>vgic_get_irq</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct vgic_irq *vgic_get_irq(struct kvm *kvm, struct kvm_vcpu *vcpu, u32 intid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dbc38)
Location: virt/kvm/arm/vgic/vgic.c:90
Inline: True
Direct callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_fold_lr_state
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_fold_lr_state
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_read_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_sactive
  - virt/kvm/arm/vgic/vgic-mmio.c:__vgic_mmio_write_cactive
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_active
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_enable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_group
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_read_sgipend
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_read_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_read_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_irouter
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_ite
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_cmd_handle_mapi
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
**Symbols:**

```
ffff8000100dbc38-ffff8000100dbdec: vgic_get_irq (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
