# Function: <code>arch_try_cmpxchg128</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f377)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afedb3)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18d6c)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145a4e7)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b52106)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6f4fc)
Location: arch/x86/include/asm/cmpxchg_64.h:76
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
