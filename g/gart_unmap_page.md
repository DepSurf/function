# Function: <code>gart_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810666b0)
Location: arch/x86/kernel/amd_gart_64.c:265
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
```
**Symbols:**

```
ffffffff810666b0-ffffffff81066775: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066440)
Location: arch/x86/kernel/amd_gart_64.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff81066440-ffffffff81066505: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a0d0)
Location: arch/x86/kernel/amd_gart_64.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8106a0d0-ffffffff8106a195: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069420)
Location: arch/x86/kernel/amd_gart_64.c:265
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff81069420-ffffffff810694ed: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106dcd0)
Location: arch/x86/kernel/amd_gart_64.c:265
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8106dcd0-ffffffff8106dd9d: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81070bd0)
Location: arch/x86/kernel/amd_gart_64.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff81070bd0-ffffffff81070c9c: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81076bc0)
Location: arch/x86/kernel/amd_gart_64.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff81076bc0-ffffffff81076c97: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a760)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8107a760-ffffffff8107a832: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b850)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8107b850-ffffffff8107b922: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81082b50)
Location: arch/x86/kernel/amd_gart_64.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
**Symbols:**

```
ffffffff81082b50-ffffffff81082c22: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810845c0)
Location: arch/x86/kernel/amd_gart_64.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
**Symbols:**

```
ffffffff810845c0-ffffffff81084692: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81085320)
Location: arch/x86/kernel/amd_gart_64.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
```
**Symbols:**

```
ffffffff81085320-ffffffff810853fa: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094290)
Location: arch/x86/kernel/amd_gart_64.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff81094290-ffffffff8109436a: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6480)
Location: arch/x86/kernel/amd_gart_64.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810a6480-ffffffff810a6584: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bf490)
Location: arch/x86/kernel/amd_gart_64.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810bf490-ffffffff810bf549: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c2b50)
Location: arch/x86/kernel/amd_gart_64.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810c2b50-ffffffff810c2c2a: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810caf90)
Location: arch/x86/kernel/amd_gart_64.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810caf90-ffffffff810cb06a: gart_unmap_page (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a850)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8107a850-ffffffff8107a922: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069f80)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff81069f80-ffffffff8106a052: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a800)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8107a800-ffffffff8107a8d2: gart_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gart_unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c900)
Location: arch/x86/kernel/amd_gart_64.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_sg
```
**Symbols:**

```
ffffffff8107c900-ffffffff8107c9d2: gart_unmap_page (STB_LOCAL)
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
