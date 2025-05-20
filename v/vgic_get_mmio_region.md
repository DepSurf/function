# Function: <code>vgic_get_mmio_region</code>

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
const struct vgic_register_region *vgic_get_mmio_region(struct kvm_vcpu *vcpu, struct vgic_io_device *iodev, gpa_t addr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e2738)
Location: virt/kvm/arm/vgic/vgic-mmio.c:759
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:dispatch_mmio_write
  - virt/kvm/arm/vgic/vgic-mmio.c:dispatch_mmio_read
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_uaccess
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_uaccess
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_v2_has_attr_regs
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_has_attr_regs
```
**Symbols:**

```
ffff8000100e2738-ffff8000100e2820: vgic_get_mmio_region (STB_GLOBAL)
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
