# Function: <code>x86_swiotlb_free_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void x86_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_addr, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff81065510)
Location: arch/x86/kernel/pci-swiotlb.c:38
Inline: False
```
**Symbols:**

```
ffffffff81065510-ffffffff81065578: x86_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void x86_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff81065260)
Location: arch/x86/kernel/pci-swiotlb.c:38
Inline: False
```
**Symbols:**

```
ffffffff81065260-ffffffff810652c8: x86_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void x86_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff81068790)
Location: arch/x86/kernel/pci-swiotlb.c:38
Inline: False
```
**Symbols:**

```
ffffffff81068790-ffffffff810687f8: x86_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void x86_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff81067ab0)
Location: arch/x86/kernel/pci-swiotlb.c:38
Inline: False
```
**Symbols:**

```
ffffffff81067ab0-ffffffff81067b18: x86_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void x86_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff8106bd40)
Location: arch/x86/kernel/pci-swiotlb.c:41
Inline: False
```
**Symbols:**

```
ffffffff8106bd40-ffffffff8106bdb2: x86_swiotlb_free_coherent (STB_GLOBAL)
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
