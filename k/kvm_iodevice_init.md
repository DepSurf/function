# Function: <code>kvm_iodevice_init</code>

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
In virt/kvm/coalesced_mmio.c (ffff8000100c0114)
Location: include/kvm/iodev.h:36
Inline: True
Inline callers:
  - virt/kvm/coalesced_mmio.c:kvm_vm_ioctl_register_coalesced_mmio
```
```
In virt/kvm/eventfd.c (ffff8000100c0858)
Location: include/kvm/iodev.h:36
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_assign_ioeventfd_idx
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e39a4)
Location: include/kvm/iodev.h:36
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_v2_init_dist_iodev
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e49c0)
Location: include/kvm/iodev.h:36
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_register_redist_iodev
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_init_dist_iodev
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e9a6c)
Location: include/kvm/iodev.h:36
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
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
