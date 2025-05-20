# Function: <code>bdev_direct_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device *bdev, sector_t sector, void **addr, long unsigned int *pfn, long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247920)
Location: fs/block_dev.c:467
Inline: False
Direct callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_zero_page_range
  - fs/dax.c:dax_clear_blocks
```
**Symbols:**

```
ffffffff81247920-ffffffff812479ef: bdev_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device *bdev, struct blk_dax_ctl *dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812700c0)
Location: fs/block_dev.c:482
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_dax_capable
  - fs/block_dev.c:bdev_dax_capable
  - fs/dax.c:dax_map_atomic
  - drivers/md/dm-linear.c:linear_direct_access
  - drivers/md/dm-stripe.c:stripe_direct_access
```
**Symbols:**

```
ffffffff812700c0-ffffffff812701b5: bdev_direct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int bdev_direct_access(struct block_device *bdev, struct blk_dax_ctl *dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812832c0)
Location: fs/block_dev.c:734
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_dax_capable
  - fs/block_dev.c:bdev_dax_capable
  - fs/dax.c:dax_map_atomic
  - drivers/md/dm-linear.c:linear_direct_access
  - drivers/md/dm-stripe.c:stripe_direct_access
```
**Symbols:**

```
ffffffff812832c0-ffffffff812833b5: bdev_direct_access (STB_GLOBAL)
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<b>Param added. </b>
<code>struct blk_dax_ctl *dax</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t sector</code>
</li>
<li>
<b>Param removed. </b>
<code>void **addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long int size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
