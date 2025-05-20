# Function: <code>SetPagePrivate</code>

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
In kernel/events/ring_buffer.c (ffffffff81185bd5)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff811dccfb)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:putback_active_hugepage
```
```
In mm/memory_hotplug.c (ffffffff811efd9d)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff811f226c)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffff81205af6)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812074a0)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_putback
```
```
In fs/buffer.c (ffffffff8124390a)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/ext4/crypto.c (ffffffff812e5482)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c3808)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff814c555d)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_alloc_pages
```
```
In drivers/md/bitmap.c (ffffffff8169b943)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff81197ba6)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff811fe1e9)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81fb6fb4)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81211158)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffff8122a350)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In fs/buffer.c (ffffffff8126ba43)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/crypto/crypto.c (ffffffff81288d14)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In drivers/xen/grant-table.c (ffffffff81515bcd)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_alloc_pages
```
```
In drivers/md/bitmap.c (ffffffff816fca7c)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff811a7594)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8120ecb9)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ff39c9)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81223318)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffff8123c8a0)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In fs/buffer.c (ffffffff8127eb83)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8129d9de)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8154204d)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_alloc_pages
```
```
In drivers/md/bitmap.c (ffffffff8172e64c)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff811aed1b)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8121a559)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff820d6184)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8122ed3a)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812484c7)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8124b2f6)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8128ca61)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812ac698)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815564bd)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff817475aa)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff811c28ab)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff812356c9)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff826dedcf)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124aec4)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81268689)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8126b5af)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812aefb4)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812cfeb8)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In drivers/xen/grant-table.c (ffffffff815b9fbd)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff817b983a)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff811e2c01)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff81258609)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8270930d)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126edc0)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffff8128cfe7)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81290156)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812d7486)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812fa787)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In drivers/xen/grant-table.c (ffffffff815f1e2d)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818019ea)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff811f3071)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8126ccd9)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828c05b2)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81282afc)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812a1f67)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a5246)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812ec996)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8130fb07)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff8132460d)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160cd9c)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff8182dbfb)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff8120ad82)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8128810a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828d9939)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8129ecb2)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812bd276)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c064e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8130e141)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81336f20)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8134b81f)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81641a40)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff8187024b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff81218062)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff81297d0a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828e1d8f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ae552)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812cf166)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d259b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff81321161)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8134ab00)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff81363aef)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81663050)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff818a204b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff81243bb2)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff812cb3ca)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/memory_hotplug.c (ffffffff812e15ea)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812e4f0d)
Location: include/linux/page-flags.h:357
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81305727)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/userfaultfd.c (ffffffff81308878)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8135ac44)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff81390269)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6e6)
Location: include/linux/page-flags.h:357
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817135f2)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff81972de0)
Location: include/linux/page-flags.h:357
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8124e242)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff812d6fea)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/memory_hotplug.c (ffffffff812ec53a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812ef8e8)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81311487)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/userfaultfd.c (ffffffff8131465f)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff81368a84)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813a18a9)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc5b)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/xen/grant-table.c (ffffffff817304e2)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff81977d06)
Location: include/linux/page-flags.h:366
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff81252b76)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/memory_hotplug.c (ffffffff812c6dda)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812f65d1)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81317551)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In fs/buffer.c (ffffffff8136ff41)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813a8a49)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d70)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/xen/grant-table.c (ffffffff81714070)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff8195b812)
Location: include/linux/page-flags.h:366
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8128e447)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/migrate.c (ffffffff81340c12)
Location: include/linux/page-flags.h:380
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81363ab1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/bootmem_info.c (ffffffff8136cb0a)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/buffer.c (ffffffff813beaa4)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813f81a3)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff81413010)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/xen/grant-table.c (ffffffff81790aa8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff81a0100b)
Location: include/linux/page-flags.h:380
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff812e344e)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/zsmalloc.c (ffffffff813dff31)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/bootmem_info.c (ffffffff813eae8a)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff81e78601)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff818c9973)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
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
In kernel/events/ring_buffer.c (ffffffff8134babe)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/zsmalloc.c (ffffffff81466e11)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/bootmem_info.c (ffffffff83ec85a0)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff8206a3bf)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81a1a73c)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
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
In kernel/events/ring_buffer.c (ffffffff8137cb0e)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/zsmalloc.c (ffffffff8149c324)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/bootmem_info.c (ffffffff836ed610)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff8153342e)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81a635bc)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
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
In kernel/events/ring_buffer.c (ffffffff813a5d6b)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/zsmalloc.c (ffffffff814cba44)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/bootmem_info.c (ffffffff83920610)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff81568356)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81ab5ddc)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
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
In kernel/events/ring_buffer.c (ffff8000102a2b44)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffff80001033611c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffff80001034e068)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff800010350450)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In mm/zsmalloc.c (ffff800010374424)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffff8000103786a0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffff8000103d9498)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffff80001040b304)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffff80001042a5bc)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffff80001082cd88)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffff800010af6fe0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (c04d26b4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/migrate.c (c0551b90)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In mm/zsmalloc.c (c0560290)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In fs/buffer.c (c05b21c8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/crypto/crypto.c (c05d8540)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (c05f2fcc)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/md/md-bitmap.c (c0bd7910)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (c000000000354f5c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (c0000000004108fc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (c000000001385410)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c000000000434210)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (c000000000465bbc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/userfaultfd.c (c00000000046ab94)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (c0000000004dbb78)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (c000000000517ea0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (c00000000053b0ec)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/md/md-bitmap.c (c000000000be3080)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffe0001d180c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffe0002321a4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/migrate.c (ffffffe00023f0ae)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffe00024c856)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
```
```
In mm/userfaultfd.c (ffffffe00024fdfc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffe0002928ea)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffe0002b4fc2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8068)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8ce4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff812106b2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff812902ea)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828cac43)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6b32)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c7746)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812cab7b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff81319741)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff813430e0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8135c0cf)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81628ec0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff81847ecb)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff81203442)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff81281f7a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828c3368)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812985d2)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812b8786)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bbb17)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8130a301)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81333dc0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd6f)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8180f52b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff8120e452)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8128e0fa)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828dd9c3)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a4942)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c5556)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c898b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff81317211)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81340bb0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff81359b9f)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81656e90)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff818974fb)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In kernel/events/ring_buffer.c (ffffffff8121d362)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/hugetlb.c (ffffffff8129de9a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/memory_hotplug.c (ffffffff828e2dda)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b54c1)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812d6036)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d969a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff813285c1)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81353eb0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8136d2af)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8167148c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/md/md-bitmap.c (ffffffff818b35db)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
</details>
</li>
</ul>

## Differences
