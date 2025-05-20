# Function: <code>set_page_dirty_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198b10)
Location: mm/page-writeback.c:2587
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff81198b10-ffffffff81198b50: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ad950)
Location: mm/page-writeback.c:2632
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff811ad950-ffffffff811ad99f: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bdeb0)
Location: mm/page-writeback.c:2599
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff811bdeb0-ffffffff811bdeff: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c6060)
Location: mm/page-writeback.c:2602
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff811c6060-ffffffff811c60af: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dae70)
Location: mm/page-writeback.c:2585
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff811dae70-ffffffff811daebf: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fc350)
Location: mm/page-writeback.c:2586
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff811fc350-ffffffff811fc3a0: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120e850)
Location: mm/page-writeback.c:2580
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_bio_complete
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_unmap_user
```
**Symbols:**

```
ffffffff8120e850-ffffffff8120e8a0: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e370)
Location: mm/page-writeback.c:2588
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff8121e370-ffffffff8121e3c3: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122be10)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff8122be10-ffffffff8122be63: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812587a0)
Location: mm/page-writeback.c:2602
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff812587a0-ffffffff812587f3: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81262db0)
Location: mm/page-writeback.c:2600
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff81262db0-ffffffff81262e03: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812677d0)
Location: mm/page-writeback.c:2600
Inline: False
Direct callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff812677d0-ffffffff81267823: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a4330)
Location: mm/page-writeback.c:2629
Inline: False
Direct callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff812a4330-ffffffff812a4383: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fc5d0)
Location: mm/page-writeback.c:2740
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
**Symbols:**

```
ffffffff812fc5d0-ffffffff812fc64f: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813668e0)
Location: mm/page-writeback.c:2878
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
**Symbols:**

```
ffffffff813668e0-ffffffff8136695f: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81398f50)
Location: mm/page-writeback.c:2819
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
**Symbols:**

```
ffffffff81398f50-ffffffff81398fcf: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c2d50)
Location: mm/page-writeback.c:2798
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
  - block/bio-integrity.c:bio_integrity_unpin_bvec
```
**Symbols:**

```
ffffffff813c2d50-ffffffff813c2dcc: set_page_dirty_lock (STB_GLOBAL)
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
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bc340)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffff8000102bc340-ffff8000102bc3ec: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6cd8)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
c04e6cd8-c04e6d98: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003730d0)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
c0000000003730d0-c0000000003731b0: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001dda84)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffe0001dda84-ffffffe0001ddaf6: set_page_dirty_lock (STB_GLOBAL)
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
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224460)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff81224460-ffffffff812244b3: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217610)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff81217610-ffffffff81217663: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81222200)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff81222200-ffffffff81222253: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231650)
Location: mm/page-writeback.c:2592
Inline: False
Direct callers:
  - mm/gup.c:put_user_pages_dirty_lock
  - mm/memory.c:__access_remote_vm
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_release_user_pages
  - block/bio.c:bio_set_pages_dirty
```
**Symbols:**

```
ffffffff81231650-ffffffff8123169a: set_page_dirty_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
