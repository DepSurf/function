# Function: <code>xen_swiotlb_dma_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d43f0)
Location: drivers/xen/swiotlb-xen.c:665
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
```
**Symbols:**

```
ffffffff814d43f0-ffffffff814d44ab: xen_swiotlb_dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525053)
Location: drivers/xen/swiotlb-xen.c:665
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
```
**Symbols:**

```
ffffffff81524f60-ffffffff8152502b: xen_swiotlb_dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81551513)
Location: drivers/xen/swiotlb-xen.c:667
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
```
**Symbols:**

```
ffffffff81551420-ffffffff815514eb: xen_swiotlb_dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81565cd0)
Location: drivers/xen/swiotlb-xen.c:659
Inline: False
```
**Symbols:**

```
ffffffff81565cd0-ffffffff81565d9b: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815c9e70)
Location: drivers/xen/swiotlb-xen.c:659
Inline: False
```
**Symbols:**

```
ffffffff815c9e70-ffffffff815c9f3b: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81602a90)
Location: drivers/xen/swiotlb-xen.c:645
Inline: False
```
**Symbols:**

```
ffffffff81602a90-ffffffff81602b5a: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161d7b0)
Location: drivers/xen/swiotlb-xen.c:633
Inline: False
```
**Symbols:**

```
ffffffff8161d7b0-ffffffff8161d87a: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816509e0)
Location: drivers/xen/swiotlb-xen.c:545
Inline: False
```
**Symbols:**

```
ffffffff816509e0-ffffffff81650aaa: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81672f60)
Location: drivers/xen/swiotlb-xen.c:537
Inline: False
```
**Symbols:**

```
ffffffff81672f60-ffffffff8167302a: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817236b0)
Location: drivers/xen/swiotlb-xen.c:543
Inline: False
```
**Symbols:**

```
ffffffff817236b0-ffffffff81723777: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81740360)
Location: drivers/xen/swiotlb-xen.c:561
Inline: False
```
**Symbols:**

```
ffffffff81740360-ffffffff81740473: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81723e30)
Location: drivers/xen/swiotlb-xen.c:548
Inline: False
```
**Symbols:**

```
ffffffff81723e30-ffffffff81723f2d: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a2cc0)
Location: drivers/xen/swiotlb-xen.c:546
Inline: False
```
**Symbols:**

```
ffffffff817a2cc0-ffffffff817a2db9: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818dcf40)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff818dcf40-ffffffff818dd038: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a30380)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff81a30380-ffffffff81a30478: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a79b90)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff81a79b90-ffffffff81a79c88: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acc000)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff81acc000-ffffffff81acc0f3: xen_swiotlb_dma_supported (STB_LOCAL)
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
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083e018)
Location: drivers/xen/swiotlb-xen.c:537
Inline: False
```
**Symbols:**

```
ffff80001083e018-ffff80001083e0b4: xen_swiotlb_dma_supported (STB_LOCAL)
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
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81638c50)
Location: drivers/xen/swiotlb-xen.c:537
Inline: False
```
**Symbols:**

```
ffffffff81638c50-ffffffff81638d1a: xen_swiotlb_dma_supported (STB_LOCAL)
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
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81666da0)
Location: drivers/xen/swiotlb-xen.c:537
Inline: False
```
**Symbols:**

```
ffffffff81666da0-ffffffff81666e6a: xen_swiotlb_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_swiotlb_dma_supported(struct device *hwdev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681350)
Location: drivers/xen/swiotlb-xen.c:537
Inline: False
```
**Symbols:**

```
ffffffff81681350-ffffffff8168141a: xen_swiotlb_dma_supported (STB_LOCAL)
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
