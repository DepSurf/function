# Function: <code>unpin_user_page</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287a80)
Location: mm/gup.c:224
Inline: False
Direct callers:
  - mm/gup.c:undo_dev_pagemap
```
**Symbols:**

```
ffffffff81287a80-ffffffff81287b2c: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291b4d)
Location: mm/gup.c:211
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
**Symbols:**

```
ffffffff81291a00-ffffffff81291a28: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129743d)
Location: mm/gup.c:239
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
Direct callers:
  - fs/io_uring.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff81296d20-ffffffff81296d48: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7ded)
Location: mm/gup.c:251
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
Direct callers:
  - fs/io_uring.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff812d76d0-ffffffff812d76f8: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337911)
Location: mm/gup.c:240
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff81337880-ffffffff813378d8: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813aefb1)
Location: mm/gup.c:255
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
Direct callers:
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/rsrc.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff813af130-ffffffff813af188: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3591)
Location: mm/gup.c:272
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:migrate_longterm_unpinnable_pages
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/rsrc.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff813e3710-ffffffff813e3768: unpin_user_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unpin_user_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140ddb1)
Location: mm/gup.c:272
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_unpin_bvec
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/rsrc.c:io_buffer_unmap
```
**Symbols:**

```
ffffffff8140df20-ffffffff8140df75: unpin_user_page (STB_GLOBAL)
```
</details>
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
