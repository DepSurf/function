# Function: <code>__dax_zero_page_range</code>

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
int __dax_zero_page_range(struct block_device *bdev, sector_t sector, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812868b0)
Location: fs/dax.c:1169
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_page_range
```
**Symbols:**

```
ffffffff812868b0-ffffffff812869f1: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, sector_t sector, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129a840)
Location: fs/dax.c:970
Inline: False
```
**Symbols:**

```
ffffffff8129a840-ffffffff8129a981: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812a9430)
Location: fs/dax.c:902
Inline: False
```
**Symbols:**

```
ffffffff812a9430-ffffffff812a9569: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cca00)
Location: fs/dax.c:914
Inline: False
```
**Symbols:**

```
ffffffff812cca00-ffffffff812ccb35: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f70f0)
Location: fs/dax.c:1148
Inline: True
```
**Symbols:**

```
ffffffff812f70f0-ffffffff812f7225: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130c1a0)
Location: fs/dax.c:1054
Inline: True
```
**Symbols:**

```
ffffffff8130c1a0-ffffffff8130c2d4: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813336f0)
Location: fs/dax.c:1059
Inline: True
```
**Symbols:**

```
ffffffff813336f0-ffffffff81333822: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813472b0)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffff813472b0-ffffffff813473e1: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010407818)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffff800010407818-ffff800010407960: __dax_zero_page_range (STB_GLOBAL)
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
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (c0000000005130f0)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
c0000000005130f0-c0000000005132a4: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b2458)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffe0002b2458-ffffffe0002b2568: __dax_zero_page_range (STB_GLOBAL)
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
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f890)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffff8133f890-ffffffff8133f9c1: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81330550)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffff81330550-ffffffff81330681: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133d360)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffff8133d360-ffffffff8133d491: __dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __dax_zero_page_range(struct block_device *bdev, struct dax_device *dax_dev, sector_t sector, unsigned int offset, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350f50)
Location: fs/dax.c:1060
Inline: True
```
**Symbols:**

```
ffffffff81350f50-ffffffff81351081: __dax_zero_page_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dax_device *dax_dev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int length</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, offset, length</code> ➡️ <code>bdev, dax_dev, sector, offset, size</code>
</li>
</ul>
</details>
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
