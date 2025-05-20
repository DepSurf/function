# Function: <code>hmm_range_dma_unmap</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct vm_area_struct *vma, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c3460)
Location: mm/hmm.c:1236
Inline: False
```
**Symbols:**

```
ffffffff812c3460-ffffffff812c35cb: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d5490)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffff812d5490-ffffffff812d55fa: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
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
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037a810)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffff80001037a810-ffff80001037a980: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565d18)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
c0565d18-c0565f30: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046f2c0)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
c00000000046f2c0-c00000000046f50c: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe000251d4e)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffe000251d4e-ffffffe000251e58: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cda70)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffff812cda70-ffffffff812cdbda: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be8e0)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffff812be8e0-ffffffff812bea4a: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb880)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffff812cb880-ffffffff812cb9ea: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int hmm_range_dma_unmap(struct hmm_range *range, struct device *device, dma_addr_t *daddrs, bool dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc5e0)
Location: mm/hmm.c:1051
Inline: False
```
**Symbols:**

```
ffffffff812dc5e0-ffffffff812dc74a: hmm_range_dma_unmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>range, vma, device, daddrs, dirty</code> ➡️ <code>range, device, daddrs, dirty</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
