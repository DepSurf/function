# Function: <code>vgic_has_its</code>

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
bool vgic_has_its(struct kvm *kvm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4108)
Location: virt/kvm/arm/vgic/vgic-mmio-v3.c:39
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_v3r_typer
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_v3_misc
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_supports_direct_msis
Direct callers:
  - virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy
  - virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy
  - virt/kvm/arm/vgic/vgic-irqfd.c:kvm_arch_set_irq_inatomic
  - virt/kvm/arm/vgic/vgic-irqfd.c:kvm_set_msi
```
**Symbols:**

```
ffff8000100e4750-ffff8000100e479c: vgic_has_its (STB_GLOBAL)
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
