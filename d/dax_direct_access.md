# Function: <code>dax_direct_access</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cb10)
Location: drivers/dax/super.c:220
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8163cb10-ffffffff8163cb9c: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a57a0)
Location: drivers/dax/super.c:244
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816a57a0-ffffffff816a5832: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1880)
Location: drivers/dax/super.c:266
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816e1880-ffffffff816e18de: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704ca0)
Location: drivers/dax/super.c:265
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81704ca0-ffffffff81704cfe: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173eab0)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8173eab0-ffffffff8173eb10: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762c90)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81762c90-ffffffff81762cf0: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823687)
Location: drivers/dax/super.c:296
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81822a40-ffffffff81822aa2: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8183239c)
Location: drivers/dax/super.c:304
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81831750-ffffffff818317b2: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8181518c)
Location: drivers/dax/super.c:304
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81814980-ffffffff818149e2: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f9ac)
Location: drivers/dax/super.c:309
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8189f140-ffffffff8189f1a5: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8c40)
Location: drivers/dax/super.c:127
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff819e8c40-ffffffff819e8cdb: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65470)
Location: drivers/dax/super.c:149
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_iomap_direct_access
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81b65470-ffffffff81b6550b: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8a70)
Location: drivers/dax/super.c:149
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_memzero
  - fs/dax.c:dax_iomap_direct_access
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81bb8a70-ffffffff81bb8b0b: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, enum dax_access_mode mode, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d0d0)
Location: drivers/dax/super.c:149
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_memzero
  - fs/dax.c:dax_iomap_direct_access
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81c0d0d0-ffffffff81c0d16b: dax_direct_access (STB_GLOBAL)
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
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962958)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffff800010962958-ffff8000109629f4: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39854)
Location: drivers/dax/super.c:296
Inline: True
```
**Symbols:**

```
c0a39854-c0a398d4: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a189f0)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
c000000000a189f0-c000000000a18ab0: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005cff48)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffe0005cff48-ffffffe0005cffbe: dax_direct_access (STB_GLOBAL)
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
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717380)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81717380-ffffffff817173e0: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816ef8b0)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816ef8b0-ffffffff816ef910: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756150)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81756150-ffffffff817561b0: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int dax_direct_access(struct dax_device *dax_dev, long unsigned int pgoff, long int nr_pages, void **kaddr, pfn_t *pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817715c0)
Location: drivers/dax/super.c:296
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff817715c0-ffffffff81771620: dax_direct_access (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>enum dax_access_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dax_dev, pgoff, nr_pages, kaddr, pfn</code> ➡️ <code>dax_dev, pgoff, nr_pages, mode, kaddr, pfn</code>
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
