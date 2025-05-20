# Function: <code>bdev_dax_pgoff</code>

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
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cec9)
Location: drivers/dax/super.c:49
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/md/dm-linear.c:linear_dax_flush
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_flush
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8163c980-ffffffff8163c9c5: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5bd3)
Location: drivers/dax/super.c:52
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816a5610-ffffffff816a5655: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1840)
Location: drivers/dax/super.c:52
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816e1840-ffffffff816e1879: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704c60)
Location: drivers/dax/super.c:52
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81704c60-ffffffff81704c99: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ea70)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8173ea70-ffffffff8173eaa9: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762c50)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81762c50-ffffffff81762c89: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8182362d)
Location: drivers/dax/super.c:46
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81822a00-ffffffff81822a39: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81832340)
Location: drivers/dax/super.c:46
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81831710-ffffffff8183174a: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81815130)
Location: drivers/dax/super.c:46
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81814940-ffffffff81814977: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f950)
Location: drivers/dax/super.c:100
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff8189f100-ffffffff8189f137: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
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
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff8000109628f0)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffff8000109628f0-ffff800010962954: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39804)
Location: drivers/dax/super.c:46
Inline: True
```
**Symbols:**

```
c0a39804-c0a39854: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a189a0)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
c000000000a189a0-c000000000a189e4: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005cfef2)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffe0005cfef2-ffffffe0005cff48: bdev_dax_pgoff (STB_GLOBAL)
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
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717340)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81717340-ffffffff81717379: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816ef870)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff816ef870-ffffffff816ef8a9: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756110)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81756110-ffffffff81756149: bdev_dax_pgoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bdev_dax_pgoff(struct block_device *bdev, sector_t sector, size_t size, long unsigned int *pgoff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771580)
Location: drivers/dax/super.c:46
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-linear.c:linear_dax_direct_access
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81771580-ffffffff817715b9: bdev_dax_pgoff (STB_GLOBAL)
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
