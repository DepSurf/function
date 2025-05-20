# Function: <code>swiotlb_init_late</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int swiotlb_init_late(size_t size, gfp_t gfp_mask, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_xen_swiotlb_init_late
```
**Symbols:**

```
ffffffff81e6126c-ffffffff81e61322: swiotlb_init_late.cold (STB_LOCAL)
ffffffff81188a30-ffffffff81188c3a: swiotlb_init_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int swiotlb_init_late(size_t size, gfp_t gfp_mask, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_xen_swiotlb_init_late
```
**Symbols:**

```
ffffffff8205a970-ffffffff8205aa02: swiotlb_init_late.cold (STB_LOCAL)
ffffffff811c4b60-ffffffff811c4e6e: swiotlb_init_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int swiotlb_init_late(size_t size, gfp_t gfp_mask, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_xen_swiotlb_init_late
```
**Symbols:**

```
ffffffff820d91e4-ffffffff820d9269: swiotlb_init_late.cold (STB_LOCAL)
ffffffff811d78b0-ffffffff811d7bcd: swiotlb_init_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int swiotlb_init_late(size_t size, gfp_t gfp_mask, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:426
Inline: False
```
**Symbols:**

```
ffffffff821b49d3-ffffffff821b4a86: swiotlb_init_late.cold (STB_LOCAL)
ffffffff811ecc30-ffffffff811ed06e: swiotlb_init_late (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
