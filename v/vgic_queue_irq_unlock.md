# Function: <code>vgic_queue_irq_unlock</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool vgic_queue_irq_unlock(struct kvm *kvm, struct vgic_irq *irq, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc230)
Location: virt/kvm/arm/vgic/vgic.c:334
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
```
**Symbols:**

```
ffff8000100dc230-ffff8000100dc494: vgic_queue_irq_unlock (STB_GLOBAL)
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
