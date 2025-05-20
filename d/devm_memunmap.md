# Function: <code>devm_memunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b5a0)
Location: kernel/memremap.c:145
Inline: True
```
**Symbols:**

```
ffffffff8118b5a0-ffffffff8118b5d8: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119dc70)
Location: kernel/memremap.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8119dc70-ffffffff8119dca8: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811ad690)
Location: kernel/memremap.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff811ad690-ffffffff811ad6c8: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b4b70)
Location: kernel/memremap.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff811b4b70-ffffffff811b4b99: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c9250)
Location: kernel/memremap.c:178
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff811c9250-ffffffff811c9279: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811e91b0)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff811e91b0-ffffffff811e91d9: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811f9ec0)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff811f9ec0-ffffffff811f9ee9: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/iomem.c (ffffffff81211e59)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81211e59-ffffffff81211e6c: devm_memunmap.cold (STB_LOCAL)
ffffffff81211e30-ffffffff81211e59: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8121f620)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8121f620-ffffffff8121f649: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8124b8c0)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8124b8c0-ffffffff8124b8e9: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81255cb0)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81255cb0-ffffffff81255cd9: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8125a270)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8125a270-ffffffff8125a299: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81295e40)
Location: kernel/iomem.c:162
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81295e40-ffffffff81295e69: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff812ebbf0)
Location: kernel/iomem.c:162
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff812ebbf0-ffffffff812ebc35: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81355cc0)
Location: kernel/iomem.c:162
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81355cc0-ffffffff81355d05: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81387350)
Location: kernel/iomem.c:162
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81387350-ffffffff81387395: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813b0ef0)
Location: kernel/iomem.c:159
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff813b0ef0-ffffffff813b0f35: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffff8000102ab998)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffff8000102ab998-ffff8000102ab9f0: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c04d8dbc)
Location: kernel/iomem.c:162
Inline: True
```
**Symbols:**

```
c04d8dbc-c04d8e0c: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c00000000035fe50)
Location: kernel/iomem.c:162
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
c00000000035fe50-c00000000035fea8: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d3568)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffe0001d3568-ffffffe0001d35ba: devm_memunmap (STB_GLOBAL)
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
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81217c70)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81217c70-ffffffff81217c99: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8120ae80)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff8120ae80-ffffffff8120aea9: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81215a10)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81215a10-ffffffff81215a39: devm_memunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_memunmap(struct device *dev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81224a10)
Location: kernel/iomem.c:162
Inline: True
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
```
**Symbols:**

```
ffffffff81224a10-ffffffff81224a39: devm_memunmap (STB_GLOBAL)
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
