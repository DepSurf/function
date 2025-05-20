# Function: <code>dma_common_get_sgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8155d8e0)
Location: drivers/base/dma-mapping.c:228
Inline: False
```
**Symbols:**

```
ffffffff8155d8e0-ffffffff8155d969: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815b1b20)
Location: drivers/base/dma-mapping.c:227
Inline: False
```
**Symbols:**

```
ffffffff815b1b20-ffffffff815b1bb0: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815e10f0)
Location: drivers/base/dma-mapping.c:230
Inline: True
```
**Symbols:**

```
ffffffff815e10f0-ffffffff815e1184: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f5f40)
Location: drivers/base/dma-mapping.c:208
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable
```
**Symbols:**

```
ffffffff815f5f40-ffffffff815f5fd4: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165dc70)
Location: drivers/base/dma-mapping.c:205
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable
```
**Symbols:**

```
ffffffff8165dc70-ffffffff8165dd04: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t handle, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110c6b0)
Location: kernel/dma/mapping.c:204
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable
```
**Symbols:**

```
ffffffff8110c6b0-ffffffff8110c744: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811182e0)
Location: kernel/dma/mapping.c:111
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable
```
**Symbols:**

```
ffffffff811182e0-ffffffff81118390: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122650)
Location: kernel/dma/mapping.c:111
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable
```
**Symbols:**

```
ffffffff81122650-ffffffff811226ff: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112eb90)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff8112eb90-ffffffff8112ec30: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d5e0)
Location: kernel/dma/mapping.c:111
Inline: False
```
**Symbols:**

```
ffffffff8113d5e0-ffffffff8113d68f: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81139a20)
Location: kernel/dma/ops_helpers.c:11
Inline: False
```
**Symbols:**

```
ffffffff81139a20-ffffffff81139acf: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8113ab70)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff8113ab70-ffffffff8113abe1: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8115dab0)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff8115dab0-ffffffff8115db1a: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff81187a50)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff81187a50-ffffffff81187ac9: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811c36a0)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff811c36a0-ffffffff811c3719: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811d61f0)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff811d61f0-ffffffff811d6269: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811eb220)
Location: kernel/dma/ops_helpers.c:18
Inline: False
```
**Symbols:**

```
ffffffff811eb220-ffffffff811eb299: dma_common_get_sgtable (STB_GLOBAL)
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
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010194090)
Location: kernel/dma/mapping.c:111
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffff800010194090-ffff80001019418c: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e13e8)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
c03e13e8-c03e1478: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f43c0)
Location: kernel/dma/mapping.c:111
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
c0000000001f43c0-c0000000001f449c: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe00012636e)
Location: kernel/dma/mapping.c:111
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffe00012636e-ffffffe0001263ec: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81127170)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff81127170-ffffffff81127210: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119bd0)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff81119bd0-ffffffff81119c70: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81125060)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff81125060-ffffffff81125100: dma_common_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dma_common_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811316a0)
Location: kernel/dma/mapping.c:111
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff811316a0-ffffffff81131740: dma_common_get_sgtable (STB_GLOBAL)
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
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t handle</code>
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
