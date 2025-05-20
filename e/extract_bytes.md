# Function: <code>extract_bytes</code>

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
long unsigned int extract_bytes(u64 data, unsigned int offset, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e3e2c)
Location: virt/kvm/arm/vgic/vgic-mmio-v3.c:20
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_pendbase
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_propbase
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_v3r_typer
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_irouter
Direct callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_baser
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_baser
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_baser
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_creadr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_cwriter
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_cbaser
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_typer
```
**Symbols:**

```
ffff8000100e4678-ffff8000100e46cc: extract_bytes (STB_GLOBAL)
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
