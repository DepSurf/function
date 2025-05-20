# Function: <code>swiotlb_map</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81119b60)
Location: kernel/dma/swiotlb.c:626
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81119b60-ffffffff81119d1b: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:655
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81124878-ffffffff81124892: swiotlb_map.cold (STB_LOCAL)
ffffffff81124590-ffffffff81124745: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81130840-ffffffff8113085a: swiotlb_map.cold (STB_LOCAL)
ffffffff81130510-ffffffff811306c2: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113f2f0)
Location: kernel/dma/swiotlb.c:663
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8113f2f0-ffffffff8113f4de: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113a9d0)
Location: kernel/dma/swiotlb.c:678
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff8113a9d0-ffffffff8113ac11: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113bd30)
Location: kernel/dma/swiotlb.c:630
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff8113bd30-ffffffff8113bf6e: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:677
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81cb06b6-ffffffff81cb06cb: swiotlb_map.cold (STB_LOCAL)
ffffffff8115ee30-ffffffff8115f07d: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:706
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81e613b6-ffffffff81e613ca: swiotlb_map.cold (STB_LOCAL)
ffffffff81188fc0-ffffffff8118923c: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:883
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8205aa4b-ffffffff8205aa5f: swiotlb_map.cold (STB_LOCAL)
ffffffff811c53a0-ffffffff811c561c: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:908
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff820d92b2-ffffffff820d92c6: swiotlb_map.cold (STB_LOCAL)
ffffffff811d7f70-ffffffff811d81f8: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t swiotlb_map(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:1472
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff821b4b3d-ffffffff821b4b51: swiotlb_map.cold (STB_LOCAL)
ffffffff811ed9b0-ffffffff811edc1c: swiotlb_map (STB_GLOBAL)
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
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010196e58)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffff800010196e58-ffff800010197040: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/swiotlb.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f73a0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
c0000000001f73a0-c0000000001f7644: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe000128708)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffe000128708-ffffffe00012887e: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81128ff0-ffffffff8112900a: swiotlb_map.cold (STB_LOCAL)
ffffffff81128cc0-ffffffff81128e72: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8111b880-ffffffff8111b89a: swiotlb_map.cold (STB_LOCAL)
ffffffff8111b550-ffffffff8111b702: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81126d10-ffffffff81126d2a: swiotlb_map.cold (STB_LOCAL)
ffffffff811269e0-ffffffff81126b92: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool swiotlb_map(struct device *dev, phys_addr_t *phys, dma_addr_t *dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:662
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81133360-ffffffff8113337a: swiotlb_map.cold (STB_LOCAL)
ffffffff81133020-ffffffff811331e9: swiotlb_map (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t paddr</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t *phys</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t *dma_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, phys, dma_addr, size, dir, attrs</code> ➡️ <code>dev, paddr, size, dir, attrs</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>dma_addr_t</code>
</li>
</ul>
</details>
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
