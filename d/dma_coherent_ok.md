# Function: <code>dma_coherent_ok</code>

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
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110ce0c)
Location: kernel/dma/direct.c:54
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8110e493)
Location: kernel/dma/swiotlb.c:694
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118b13)
Location: kernel/dma/direct.c:90
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122f8e)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f3ce)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113dc80)
Location: kernel/dma/direct.c:73
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8113dc80-ffffffff8113dd02: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811385f5)
Location: kernel/dma/direct.c:68
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff811383d0-ffffffff811384bc: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139713)
Location: kernel/dma/direct.c:68
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff811394f0-ffffffff811395dc: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115c6e1)
Location: kernel/dma/direct.c:68
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8115c830-ffffffff8115c91c: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8118646b)
Location: kernel/dma/direct.c:68
Inline: True
```
**Symbols:**

```
ffffffff811865d0-ffffffff811866e5: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c1e80)
Location: kernel/dma/direct.c:68
Inline: True
```
**Symbols:**

```
ffffffff811c2030-ffffffff811c2145: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d49b5)
Location: kernel/dma/direct.c:69
Inline: True
```
**Symbols:**

```
ffffffff811d4b70-ffffffff811d4c8c: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811e98a5)
Location: kernel/dma/direct.c:69
Inline: True
```
**Symbols:**

```
ffffffff811e9a70-ffffffff811e9b7d: dma_coherent_ok (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194d94)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (c03e1af0)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f5110)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126c54)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
bool dma_coherent_ok(struct device *dev, phys_addr_t phys, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127830)
Location: kernel/dma/direct.c:79
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81127830-ffffffff811278b2: dma_coherent_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a40e)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112589e)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131ede)
Location: kernel/dma/direct.c:79
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
<b>Flavor</b>
<ul>
</ul>
