# Function: <code>readahead_gfp_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b0ff6)
Location: include/linux/pagemap.h:212
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81276e1c)
Location: include/linux/pagemap.h:212
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81312e2f)
Location: include/linux/pagemap.h:212
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c15e3)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff8128aaec)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81328ddf)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c989b)
Location: include/linux/pagemap.h:239
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff8129793c)
Location: include/linux/pagemap.h:239
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff8131e87d)
Location: include/linux/pagemap.h:239
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811de71b)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff812babbc)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81342e9c)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811fff38)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff812e3785)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/ext4/readpage.c (ffffffff81370da2)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212808)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff812f84b8)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81389247)
Location: include/linux/pagemap.h:237
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812221f8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81318ae8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b340e)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8122fca8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff8132b928)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813cc5de)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125ce34)
Location: include/linux/pagemap.h:262
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81364d65)
Location: include/linux/pagemap.h:262
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812671a6)
Location: include/linux/pagemap.h:298
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81371ce5)
Location: include/linux/pagemap.h:298
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126b959)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81377e11)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a8629)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff813c44fd)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813018f9)
Location: include/linux/pagemap.h:490
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136bfc9)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139e249)
Location: include/linux/pagemap.h:492
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c7ee9)
Location: include/linux/pagemap.h:563
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bf538)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffff8000103e6ecc)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffff8000104a4a18)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eaf98)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (c05bec20)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c06665e0)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c000000000378194)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (c0000000004ed3c0)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0000000005d1b08)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e16a4)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffe00029c002)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffe000325b42)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812282f8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81323f08)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c4bbe)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121b438)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81314aa8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b563e)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81226098)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff813219d8)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c204e)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81235398)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In fs/mpage.c (ffffffff81333738)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813d71ce)
Location: include/linux/pagemap.h:224
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>

## Differences
