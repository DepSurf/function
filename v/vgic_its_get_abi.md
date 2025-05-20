# Function: <code>vgic_its_get_abi</code>

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
const struct vgic_its_abi *vgic_its_get_abi(struct vgic_its *its);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e9734)
Location: virt/kvm/arm/vgic/vgic-its.c:185
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_commit_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:handle_l1_dte
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_dte
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_write_its_baser
  - virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_typer
```
**Symbols:**

```
ffff8000100e9100-ffff8000100e911c: vgic_its_get_abi (STB_GLOBAL)
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
