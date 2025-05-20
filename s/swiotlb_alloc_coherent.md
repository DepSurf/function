# Function: <code>swiotlb_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412400)
Location: lib/swiotlb.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81412400-ffffffff8141254e: swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a140)
Location: lib/swiotlb.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff8145a140-ffffffff8145a297: swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478ba0)
Location: lib/swiotlb.c:671
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81478ba0-ffffffff81478cf8: swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81481ee0)
Location: lib/swiotlb.c:671
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81481ee0-ffffffff81482036: swiotlb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *swiotlb_alloc_coherent(struct device *hwdev, size_t size, dma_addr_t *dma_handle, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bdda0)
Location: lib/swiotlb.c:713
Inline: False
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_alloc_coherent
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
**Symbols:**

```
ffffffff814bdda0-ffffffff814bdfb2: swiotlb_alloc_coherent (STB_GLOBAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
