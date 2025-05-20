# Function: <code>vgic_irq_set_phys_active</code>

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
void vgic_irq_set_phys_active(struct vgic_irq *irq, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc1e0)
Location: virt/kvm/arm/vgic/vgic.c:195
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_fold_lr_state
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_fold_lr_state
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
```
**Symbols:**

```
ffff8000100dc1e0-ffff8000100dc230: vgic_irq_set_phys_active (STB_GLOBAL)
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
