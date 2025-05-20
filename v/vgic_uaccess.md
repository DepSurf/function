# Function: <code>vgic_uaccess</code>

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
int vgic_uaccess(struct kvm_vcpu *vcpu, struct vgic_io_device *dev, bool is_write, int offset, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e2a30)
Location: virt/kvm/arm/vgic/vgic-mmio.c:816
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_v2_dist_uaccess
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_v2_cpuif_uaccess
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_redist_uaccess
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dist_uaccess
```
**Symbols:**

```
ffff8000100e2a30-ffff8000100e2b44: vgic_uaccess (STB_GLOBAL)
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
