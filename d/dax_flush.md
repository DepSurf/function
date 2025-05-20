# Function: <code>dax_flush</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dax_flush(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163d310)
Location: drivers/dax/super.c:258
Inline: True
Direct callers:
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/md/dm-linear.c:linear_dax_flush
  - drivers/md/dm-stripe.c:stripe_dax_flush
```
**Symbols:**

```
ffffffff8163d310-ffffffff8163d345: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5840)
Location: drivers/dax/super.c:284
Inline: False
Direct callers:
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff816a5840-ffffffff816a5867: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e19f0)
Location: drivers/dax/super.c:310
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff816e19f0-ffffffff816e1a16: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704e10)
Location: drivers/dax/super.c:309
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81704e10-ffffffff81704e36: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ec70)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8173ec70-ffffffff8173ec95: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762e50)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81762e50-ffffffff81762e75: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822c10)
Location: drivers/dax/super.c:370
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81822c10-ffffffff81822c35: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831920)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81831920-ffffffff81831945: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814b50)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81814b50-ffffffff81814b72: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f310)
Location: drivers/dax/super.c:370
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff8189f310-ffffffff8189f332: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8fb0)
Location: drivers/dax/super.c:209
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff819e8fb0-ffffffff819e8fea: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b655d0)
Location: drivers/dax/super.c:254
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81b655d0-ffffffff81b6560a: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8bf0)
Location: drivers/dax/super.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_memzero
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81bb8bf0-ffffffff81bb8c2a: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d250)
Location: drivers/dax/super.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_memzero
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_iomap_copy_around
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff81c0d250-ffffffff81c0d28a: dax_flush (STB_GLOBAL)
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
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962bb8)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffff800010962bb8-ffff800010962c04: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a398d4)
Location: drivers/dax/super.c:357
Inline: False
```
**Symbols:**

```
c0a398d4-c0a398ec: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18c50)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
c000000000a18c50-c000000000a18c98: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005cffbe)
Location: drivers/dax/super.c:357
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffe0005cffbe-ffffffe0005cffd8: dax_flush (STB_GLOBAL)
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
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717540)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81717540-ffffffff81717565: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efa70)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff816efa70-ffffffff816efa95: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756310)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81756310-ffffffff81756335: dax_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_flush(struct dax_device *dax_dev, void *addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771780)
Location: drivers/dax/super.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81771780-ffffffff817717a5: dax_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int pgoff</code>
</li>
<li>
<b>Param reordered. </b>
<code>dax_dev, pgoff, addr, size</code> ➡️ <code>dax_dev, addr, size</code>
</li>
</ul>
</details>
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
