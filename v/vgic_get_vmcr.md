# Function: <code>vgic_get_vmcr</code>

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
void vgic_get_vmcr(struct kvm_vcpu *vcpu, struct vgic_vmcr *vmcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e2608)
Location: virt/kvm/arm/vgic/vgic-mmio.c:660
Inline: False
Direct callers:
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_grpen1
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_grpen0
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_bpr1
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_bpr0
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_pmr
  - arch/arm64/kvm/vgic-sys-reg-v3.c:access_gic_ctlr
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_vcpuif
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_read_vcpuif
```
**Symbols:**

```
ffff8000100e2608-ffff8000100e265c: vgic_get_vmcr (STB_GLOBAL)
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
