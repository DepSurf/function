# Function: <code>xen_swiotlb_free_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d52f0)
Location: drivers/xen/swiotlb-xen.c:348
Inline: False
```
**Symbols:**

```
ffffffff814d52f0-ffffffff814d54ef: xen_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815260a0)
Location: drivers/xen/swiotlb-xen.c:348
Inline: False
```
**Symbols:**

```
ffffffff815260a0-ffffffff815262bb: xen_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815525b0)
Location: drivers/xen/swiotlb-xen.c:352
Inline: False
```
**Symbols:**

```
ffffffff815525b0-ffffffff815527cb: xen_swiotlb_free_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81566d80)
Location: drivers/xen/swiotlb-xen.c:354
Inline: False
```
**Symbols:**

```
ffffffff81566d80-ffffffff81566f9c: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815caf30)
Location: drivers/xen/swiotlb-xen.c:354
Inline: False
```
**Symbols:**

```
ffffffff815caf30-ffffffff815cb158: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81603790)
Location: drivers/xen/swiotlb-xen.c:340
Inline: False
```
**Symbols:**

```
ffffffff81603790-ffffffff816039ad: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e880)
Location: drivers/xen/swiotlb-xen.c:343
Inline: False
```
**Symbols:**

```
ffffffff8161e880-ffffffff8161ea41: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff816517e0-ffffffff81651b9e: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff81652032-ffffffff81652045: xen_swiotlb_free_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81673d90)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff81673d90-ffffffff81674145: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724c00)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff81724c00-ffffffff81724fb8: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81741a90)
Location: drivers/xen/swiotlb-xen.c:334
Inline: False
```
**Symbols:**

```
ffffffff81741a90-ffffffff81741f70: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81725440)
Location: drivers/xen/swiotlb-xen.c:321
Inline: False
```
**Symbols:**

```
ffffffff81725440-ffffffff81725953: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:319
Inline: False
```
**Symbols:**

```
ffffffff817a42e0-ffffffff817a47f5: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff81cf6770-ffffffff81cf679f: xen_swiotlb_free_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:168
Inline: False
```
**Symbols:**

```
ffffffff818dd6b0-ffffffff818dd9ed: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff81ebe867-ffffffff81ebe89e: xen_swiotlb_free_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:168
Inline: False
```
**Symbols:**

```
ffffffff81a30b90-ffffffff81a30ecd: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff820949c8-ffffffff820949ff: xen_swiotlb_free_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:168
Inline: False
```
**Symbols:**

```
ffffffff81a7a3a0-ffffffff81a7a6dd: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff821157ec-ffffffff82115823: xen_swiotlb_free_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_swiotlb_free_coherent(struct device *dev, size_t size, void *vaddr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:168
Inline: False
```
**Symbols:**

```
ffffffff81accef0-ffffffff81acd22d: xen_swiotlb_free_coherent (STB_LOCAL)
ffffffff821f34b2-ffffffff821f34e9: xen_swiotlb_free_coherent.cold (STB_LOCAL)
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
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083e0b8)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffff80001083e0b8-ffff80001083e27c: xen_swiotlb_free_coherent (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81639a80)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff81639a80-ffffffff81639e35: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81667bd0)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff81667bd0-ffffffff81667f85: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_swiotlb_free_coherent(struct device *hwdev, size_t size, void *vaddr, dma_addr_t dev_addr, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81682190)
Location: drivers/xen/swiotlb-xen.c:332
Inline: False
```
**Symbols:**

```
ffffffff81682190-ffffffff81682545: xen_swiotlb_free_coherent (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_handle</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t dev_addr</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
