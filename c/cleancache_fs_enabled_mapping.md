# Function: <code>cleancache_fs_enabled_mapping</code>

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
In mm/filemap.c (ffffffff8118e47f)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8119e7c9)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812473b7)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/filemap.c (ffffffff811a1e19)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff811b42b1)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8126fc77)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff812768f8)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81313368)
Location: include/linux/cleancache.h:51
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
In mm/filemap.c (ffffffff811b1c8b)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff811c4921)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81282e77)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff8128a605)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81329306)
Location: include/linux/cleancache.h:51
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
In mm/filemap.c (ffffffff811b8998)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff811cd07f)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812907c9)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff8129759f)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8131ef1d)
Location: include/linux/cleancache.h:51
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
In mm/filemap.c (ffffffff811ca0ff)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff811e22aa)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812b3489)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff812ba82f)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813435bb)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff811eb27b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff81203b32)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812db189)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff812e3222)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81371332)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff811fbdeb)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff81216413)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812f06d9)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff812f7e94)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813897ee)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff81213ec4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff81225de7)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131205b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff813184d3)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b39c4)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff812216d4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff81233c46)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81324fbb)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff8132b333)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813ccbfd)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff8124f564)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8126128d)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8135eb4b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff81364fda)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81418f12)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/filemap.c (ffffffff812598c4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8126b68b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8136c30b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff81371eea)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8142cad7)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/filemap.c (ffffffff8125da54)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff812707f2)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81372c4b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff81378004)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81433798)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/filemap.c (ffffffff81299ce4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff812ae47d)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/mpage.c (ffffffff813c479e)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81486c4e)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/bdev.c (ffffffff815c3b9e)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - block/bdev.c:invalidate_bdev
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102aed00)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffff8000102c4118)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffff8000103df558)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffff8000103e68fc)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffff8000104a50dc)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (c04da948)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (c04eeb70)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (c05b7880)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (c05be764)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0666e2c)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (c00000000036217c)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (c00000000037e2dc)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (c0000000004e431c)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (c0000000004ed234)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0000000005d233c)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffe0001d42d2)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffe0001e4c5c)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffe0002963b4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffe00029bf74)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffe00032601a)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff81219d24)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8122c296)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131d59b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff81323913)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c51dd)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff8120cf34)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8121f370)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8130e13b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff813144b3)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b5c5d)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff81217ac4)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8122a036)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131b06b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff813213e3)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c266d)
Location: include/linux/cleancache.h:52
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
In mm/filemap.c (ffffffff81226b84)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff81239423)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8132cd0b)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
```
In fs/mpage.c (ffffffff81333137)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813d784e)
Location: include/linux/cleancache.h:52
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>

## Differences
