# Function: <code>alloc_dax_region</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817403e0)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
ffffffff817403e0-ffffffff81740553: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817645e0)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
ffffffff817645e0-ffffffff81764753: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81824150)
Location: drivers/dax/bus.c:228
Inline: False
```
**Symbols:**

```
ffffffff81824150-ffffffff81824334: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81834040)
Location: drivers/dax/bus.c:543
Inline: False
```
**Symbols:**

```
ffffffff81834040-ffffffff81834225: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817230)
Location: drivers/dax/bus.c:544
Inline: False
```
**Symbols:**

```
ffffffff81817230-ffffffff8181740e: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a1880)
Location: drivers/dax/bus.c:542
Inline: True
```
**Symbols:**

```
ffffffff818a1880-ffffffff818a1a5e: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819eafb0)
Location: drivers/dax/bus.c:572
Inline: False
```
**Symbols:**

```
ffffffff819eafb0-ffffffff819eb19f: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b67b10)
Location: drivers/dax/bus.c:572
Inline: False
```
**Symbols:**

```
ffffffff81b67b10-ffffffff81b67cff: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bbac90)
Location: drivers/dax/bus.c:601
Inline: False
```
**Symbols:**

```
ffffffff81bbac90-ffffffff81bbae12: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct range *range, int target_node, unsigned int align, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0f470)
Location: drivers/dax/bus.c:602
Inline: False
```
**Symbols:**

```
ffffffff81c0f470-ffffffff81c0f61b: alloc_dax_region (STB_GLOBAL)
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
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010963fb0)
Location: drivers/dax/bus.c:228
Inline: False
```
**Symbols:**

```
ffff800010963fb0-ffff800010964140: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3b208)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
c0a3b208-c0a3b378: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1acc0)
Location: drivers/dax/bus.c:228
Inline: False
```
**Symbols:**

```
c000000000a1acc0-c000000000a1af24: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d17a6)
Location: drivers/dax/bus.c:228
Inline: False
```
**Symbols:**

```
ffffffe0005d17a6-ffffffe0005d18da: alloc_dax_region (STB_GLOBAL)
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
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718cd0)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
ffffffff81718cd0-ffffffff81718e43: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f1200)
Location: drivers/dax/bus.c:228
Inline: True
Direct callers:
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816f1200-ffffffff816f1373: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81757aa0)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
ffffffff81757aa0-ffffffff81757c13: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dax_region *alloc_dax_region(struct device *parent, int region_id, struct resource *res, int target_node, unsigned int align, long unsigned int pfn_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772f40)
Location: drivers/dax/bus.c:228
Inline: True
```
**Symbols:**

```
ffffffff81772f40-ffffffff817730b3: alloc_dax_region (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int pfn_flags</code> ➡️ <code>long long unsigned int pfn_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct range *range</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource *res</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int pfn_flags</code>
</li>
</ul>
</details>
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
