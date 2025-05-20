# Function: <code>dma_generic_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dma_generic_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81034e00)
Location: arch/x86/kernel/pci-dma.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81034e00-ffffffff81034f24: dma_generic_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dma_generic_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81033fe0)
Location: arch/x86/kernel/pci-dma.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81033fe0-ffffffff81034118: dma_generic_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dma_generic_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81033c10)
Location: arch/x86/kernel/pci-dma.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81033c10-ffffffff81033d5e: dma_generic_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dma_generic_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81031cf0)
Location: arch/x86/kernel/pci-dma.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81031cf0-ffffffff81031e15: dma_generic_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dma_generic_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81034010)
Location: arch/x86/kernel/pci-dma.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81034010-ffffffff81034147: dma_generic_alloc_coherent (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
