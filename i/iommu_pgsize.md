# Function: <code>iommu_pgsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a700)
Location: drivers/iommu/iommu.c:1279
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8152a700-ffffffff8152a74e: iommu_pgsize.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157db40)
Location: drivers/iommu/iommu.c:1269
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8157db40-ffffffff8157db87: iommu_pgsize.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa0e0)
Location: drivers/iommu/iommu.c:1420
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff815aa0e0-ffffffff815aa127: iommu_pgsize.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bfd70)
Location: drivers/iommu/iommu.c:1470
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff815bfd70-ffffffff815bfdba: iommu_pgsize.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626390)
Location: drivers/iommu/iommu.c:1471
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff81626390-ffffffff816263da: iommu_pgsize.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660fd0)
Location: drivers/iommu/iommu.c:1477
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff81660fd0-ffffffff8166101a: iommu_pgsize.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f8a0)
Location: drivers/iommu/iommu.c:1553
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8167f8a0-ffffffff8167f8ea: iommu_pgsize.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6c90)
Location: drivers/iommu/iommu.c:1770
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816b6c90-ffffffff816b6cda: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9820)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816d9820-ffffffff816d986a: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int addr_merge, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178dac0)
Location: drivers/iommu/iommu.c:2139
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff8178dac0-ffffffff8178db0b: iommu_pgsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int addr_merge, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9830)
Location: drivers/iommu/iommu.c:2349
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff817b9830-ffffffff817b987b: iommu_pgsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int addr_merge, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c9e0)
Location: drivers/iommu/iommu.c:2380
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff8179c9e0-ffffffff8179ca2b: iommu_pgsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, size_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2404
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff818249c0-ffffffff81824b25: iommu_pgsize (STB_LOCAL)
ffffffff81d01781-ffffffff81d01839: iommu_pgsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, size_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2181
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff81964960-ffffffff81964ada: iommu_pgsize (STB_LOCAL)
ffffffff81ec9c64-ffffffff81ec9d41: iommu_pgsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, size_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2245
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff81acda40-ffffffff81acdbba: iommu_pgsize (STB_LOCAL)
ffffffff82097bb2-ffffffff82097c8f: iommu_pgsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, size_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2264
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff81b1c570-ffffffff81b1c6e1: iommu_pgsize (STB_LOCAL)
ffffffff82118bb4-ffffffff82118c8a: iommu_pgsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, size_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2553
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
**Symbols:**

```
ffffffff81b73af0-ffffffff81b73c61: iommu_pgsize (STB_LOCAL)
ffffffff821f6ac6-ffffffff821f6b9c: iommu_pgsize.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4f20)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffff8000108c4f20-ffff8000108c4fa4: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t iommu_pgsize(struct iommu_domain *domain, long unsigned int addr_merge, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc43c)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
c09bc43c-c09bc498: iommu_pgsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b110)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
c00000000096b110-c00000000096b188: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f270)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8169f270-ffffffff8169f2ba: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167cc60)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8167cc60-ffffffff8167ccaa: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd4e0)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816cd4e0-ffffffff816cd52a: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e79f0)
Location: drivers/iommu/iommu.c:1826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816e79f0-ffffffff816e7a3a: iommu_pgsize.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int iova</code>
</li>
<li>
<b>Param added. </b>
<code>phys_addr_t paddr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *count</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr_merge</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, addr_merge, size</code> ➡️ <code>domain, iova, paddr, size, count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
