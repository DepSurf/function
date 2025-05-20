# Function: <code>nvdimm_has_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815ef340)
Location: drivers/nvdimm/region_devs.c:921
Inline: False
```
**Symbols:**

```
ffffffff815ef340-ffffffff815ef399: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161c510)
Location: drivers/nvdimm/region_devs.c:969
Inline: False
```
**Symbols:**

```
ffffffff8161c510-ffffffff8161c569: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816315df)
Location: drivers/nvdimm/region_devs.c:1070
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81630550-ffffffff816305b3: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699e7f)
Location: drivers/nvdimm/region_devs.c:1091
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81698d80-ffffffff81698de4: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6155)
Location: drivers/nvdimm/region_devs.c:1131
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff816d5030-ffffffff816d5091: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7e75)
Location: drivers/nvdimm/region_devs.c:1159
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff816f6d30-ffffffff816f6d91: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81731570)
Location: drivers/nvdimm/region_devs.c:1185
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81730560-ffffffff817305bc: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81755698)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff817545f0-ffffffff8175464c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818136bd)
Location: drivers/nvdimm/region_devs.c:1233
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81813230-ffffffff8181328c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818228ad)
Location: drivers/nvdimm/region_devs.c:1233
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81822440-ffffffff8182249c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81805f0c)
Location: drivers/nvdimm/region_devs.c:1240
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81805750-ffffffff818057cc: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818912ac)
Location: drivers/nvdimm/region_devs.c:1240
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff8188fe70-ffffffff8188feec: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819daf85)
Location: drivers/nvdimm/region_devs.c:1125
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff819d9850-ffffffff819d98d9: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b549b0)
Location: drivers/nvdimm/region_devs.c:1183
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81b549b0-ffffffff81b54a39: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba7f00)
Location: drivers/nvdimm/region_devs.c:1183
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81ba7f00-ffffffff81ba7f89: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfc1a0)
Location: drivers/nvdimm/region_devs.c:1184
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81bfc1a0-ffffffff81bfc229: nvdimm_has_flush (STB_GLOBAL)
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
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956874)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffff8000109551a0-ffff800010955208: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a0457c)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
c000000000a02ee0-c000000000a02f3c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c477c)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
```
**Symbols:**

```
ffffffe0005c477c-ffffffe0005c4798: nvdimm_has_flush (STB_GLOBAL)
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
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81709d88)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81708ce0-ffffffff81708d3c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dd808)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
**Symbols:**

```
ffffffff816dc760-ffffffff816dc7bc: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81748b58)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81747ab0-ffffffff81747b0c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_has_flush(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763fd8)
Location: drivers/nvdimm/region_devs.c:1136
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:deep_flush_show
```
**Symbols:**

```
ffffffff81762eb0-ffffffff81762f0c: nvdimm_has_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
