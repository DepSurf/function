# Function: <code>cleancache_fs_enabled</code>

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
In mm/filemap.c (ffffffff8118e3f3)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In fs/mpage.c (ffffffff8124e1a3)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff812e33ab)
Location: include/linux/cleancache.h:51
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In fs/mpage.c (ffffffff812768f8)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81313368)
Location: include/linux/cleancache.h:55
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
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In fs/mpage.c (ffffffff8128a605)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81329306)
Location: include/linux/cleancache.h:55
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
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In fs/mpage.c (ffffffff8129759f)
Location: include/linux/cleancache.h:55
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8131ef1d)
Location: include/linux/cleancache.h:55
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
In mm/filemap.c (ffffffff811ca0fb)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff812ba824)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813435b7)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff812e3222)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81371332)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff812f7e94)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813897ee)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff813184d3)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b39c4)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff8132b333)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813ccbfd)
Location: include/linux/cleancache.h:56
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
In mm/filemap.c (ffffffff8124f5a5)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff81364fda)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81418f12)
Location: include/linux/cleancache.h:56
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
In mm/filemap.c (ffffffff81259905)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff81371eea)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8142cad7)
Location: include/linux/cleancache.h:56
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
In mm/filemap.c (ffffffff8125da95)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff81378004)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81433798)
Location: include/linux/cleancache.h:56
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
In mm/filemap.c (ffffffff81299d25)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff813c479e)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81486c4e)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffff8000103e68fc)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffff8000104a50dc)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (c05be764)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0666e2c)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (c0000000004ed234)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0000000005d233c)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffe00029bf74)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffe00032601a)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff81323913)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c51dd)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff813144b3)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b5c5d)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff813213e3)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c266d)
Location: include/linux/cleancache.h:56
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
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In fs/mpage.c (ffffffff81333137)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813d784e)
Location: include/linux/cleancache.h:56
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>

## Differences
