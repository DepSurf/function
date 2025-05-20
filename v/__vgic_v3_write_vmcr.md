# Function: <code>__vgic_v3_write_vmcr</code>

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
void __vgic_v3_write_vmcr(u32 vmcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dabdb0)
Location: virt/kvm/arm/hyp/vgic-v3-sr.c:429
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_bpr1
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_bpr0
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_igrpen1
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_igrpen0
Direct callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
```
**Symbols:**

```
ffff800010dacaf0-ffff800010dacafc: __vgic_v3_write_vmcr (STB_GLOBAL)
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
