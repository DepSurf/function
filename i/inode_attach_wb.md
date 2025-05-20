# Function: <code>inode_attach_wb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e8f6)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8119a861)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8123ad2e)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2486)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811af16c)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81262bd6)
Location: include/linux/writeback.h:212
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff811b22c6)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811bf80c)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81276026)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff811b8f3e)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811c799c)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81283576)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff811cd83e)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811dc7dc)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff812a6102)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff811ef372)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff811fc7cc)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff812ccbde)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81200b72)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8120f31c)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff812e1f0e)
Location: include/linux/writeback.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81218792)
Location: include/linux/writeback.h:231
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81221399)
Location: include/linux/writeback.h:231
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8130097f)
Location: include/linux/writeback.h:231
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81226013)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8122ee29)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8131304f)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8125114a)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8125bf09)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8134c9af)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8125c7da)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81266339)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff813599a9)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff812615ba)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8126ae39)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81360563)
Location: include/linux/writeback.h:234
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff812994c1)
Location: include/linux/writeback.h:235
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a4ad9)
Location: include/linux/writeback.h:235
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff813aebe3)
Location: include/linux/writeback.h:235
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef525)
Location: include/linux/writeback.h:239
Inline: True
```
```
In mm/page-writeback.c (ffffffff812ff296)
Location: include/linux/writeback.h:239
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/fs-writeback.c (ffffffff814331d3)
Location: include/linux/writeback.h:239
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135a265)
Location: include/linux/writeback.h:231
Inline: True
```
```
In mm/page-writeback.c (ffffffff81367907)
Location: include/linux/writeback.h:231
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/fs-writeback.c (ffffffff814c1542)
Location: include/linux/writeback.h:231
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138bc75)
Location: include/linux/writeback.h:226
Inline: True
```
```
In mm/page-writeback.c (ffffffff81399da7)
Location: include/linux/writeback.h:226
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/fs-writeback.c (ffffffff814f68d2)
Location: include/linux/writeback.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b57a5)
Location: include/linux/writeback.h:225
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c3a64)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In fs/fs-writeback.c (ffffffff8152b012)
Location: include/linux/writeback.h:225
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffff8000102b3230)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffff8000102be0a0)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffff8000103c8810)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (c04e0464)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c04ea358)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (c05a5174)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (c000000000369d90)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (c000000000376eec)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (c0000000004c9d58)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffe0001d8976)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffe0001e0b12)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffe000286f84)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8121e663)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81227479)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8130b62f)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81211823)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff8121a5e9)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff812fc24f)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8121c403)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff81225219)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8130941f)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8122b493)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/page-writeback.c (ffffffff812344f9)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81319d6d)
Location: include/linux/writeback.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
</ul>

## Differences
