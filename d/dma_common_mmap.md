# Function: <code>dma_common_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8155d970)
Location: drivers/base/dma-mapping.c:246
Inline: False
```
**Symbols:**

```
ffffffff8155d970-ffffffff8155d9fc: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815b1bb0)
Location: drivers/base/dma-mapping.c:245
Inline: False
```
**Symbols:**

```
ffffffff815b1bb0-ffffffff815b1c49: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815e0e00)
Location: drivers/base/dma-mapping.c:248
Inline: False
```
**Symbols:**

```
ffffffff815e0e00-ffffffff815e0e99: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f5c70)
Location: drivers/base/dma-mapping.c:226
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_mmap
```
**Symbols:**

```
ffffffff815f5c70-ffffffff815f5d04: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165db90)
Location: drivers/base/dma-mapping.c:223
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_mmap
```
**Symbols:**

```
ffffffff8165db90-ffffffff8165dc24: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110c5d0)
Location: kernel/dma/mapping.c:222
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_mmap
```
**Symbols:**

```
ffffffff8110c5d0-ffffffff8110c665: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811183d0)
Location: kernel/dma/mapping.c:151
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_mmap
```
**Symbols:**

```
ffffffff811183d0-ffffffff81118465: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122750)
Location: kernel/dma/mapping.c:173
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_mmap
```
**Symbols:**

```
ffffffff81122750-ffffffff81122848: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112ec80)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffff8112ec80-ffffffff8112ed00: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d6c0)
Location: kernel/dma/mapping.c:174
Inline: False
```
**Symbols:**

```
ffffffff8113d6c0-ffffffff8113d796: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81139ad0)
Location: kernel/dma/ops_helpers.c:27
Inline: False
```
**Symbols:**

```
ffffffff81139ad0-ffffffff81139b90: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8113abf0)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff8113abf0-ffffffff8113acaa: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8115db20)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff8115db20-ffffffff8115dbda: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81187ad0)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff81187ad0-ffffffff81187b98: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811c3730)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff811c3730-ffffffff811c37f2: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811d6280)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff811d6280-ffffffff811d6348: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811eb2b0)
Location: kernel/dma/ops_helpers.c:34
Inline: False
```
**Symbols:**

```
ffffffff811eb2b0-ffffffff811eb378: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010194290)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffff800010194290-ffff8000101943fc: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1530)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
c03e1530-c03e1638: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f4520)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
c0000000001f4520-c0000000001f4640: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000126482)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffe000126482-ffffffe000126534: dma_common_mmap (STB_GLOBAL)
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
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81127260)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffff81127260-ffffffff811272e0: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119cc0)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffff81119cc0-ffffffff81119d40: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81125150)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffff81125150-ffffffff811251d0: dma_common_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_common_mmap(struct device *dev, struct vm_area_struct *vma, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131790)
Location: kernel/dma/mapping.c:187
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_mmap_attrs
```
**Symbols:**

```
ffffffff81131790-ffffffff81131810: dma_common_mmap (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
