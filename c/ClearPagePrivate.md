# Function: <code>ClearPagePrivate</code>

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
In kernel/events/ring_buffer.c (ffffffff811852e6)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_irq_work
```
```
In mm/hugetlb.c (ffffffff811db817)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/memory_hotplug.c (ffffffff811efddc)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff811f1ce3)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/balloon_compaction.c (ffffffff812073ce)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_isolate
```
```
In fs/buffer.c (ffffffff81242cec)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/ext4/crypto.c (ffffffff812e53d6)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_restore_control_page
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c3881)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff814c55a3)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff8169c209)
Location: include/linux/page-flags.h:233
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8119714b)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fe16a)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8120f21c)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812110d5)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/zsmalloc.c (ffffffff8122a102)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/buffer.c (ffffffff8126c874)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff81288806)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In drivers/xen/grant-table.c (ffffffff81515c13)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff816fd4f1)
Location: include/linux/page-flags.h:286
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811a6b3f)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120ec3a)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812212ec)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff81223295)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/zsmalloc.c (ffffffff8123c652)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/buffer.c (ffffffff8127f8d4)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff8129d506)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In drivers/xen/grant-table.c (ffffffff81542093)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff8172f171)
Location: include/linux/page-flags.h:296
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811ae308)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a4e4)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8122ca54)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8122e32d)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/zsmalloc.c (ffffffff81248262)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff8124b85c)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8128d0e2)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff812ac176)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In drivers/xen/grant-table.c (ffffffff81555e83)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff817487e9)
Location: include/linux/page-flags.h:296
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811c1f7d)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In mm/hugetlb.c (ffffffff81235654)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81248285)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812493ed)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff81268422)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff8126bbb5)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812af8cf)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff812cf9b6)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In drivers/xen/grant-table.c (ffffffff815b9ae3)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/md-bitmap.c (ffffffff817baa71)
Location: include/linux/page-flags.h:297
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811e233e)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In mm/hugetlb.c (ffffffff81258594)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8126bcb5)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8126ed55)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff8128cdb2)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812904e7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812d7752)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff812fa176)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In drivers/xen/grant-table.c (ffffffff815f1973)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/md-bitmap.c (ffffffff81802b11)
Location: include/linux/page-flags.h:304
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff811f27ae)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126cc66)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812805b5)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8128169a)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812a1d32)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812a54c1)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff812ecbb2)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff8130f456)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
```
```
In fs/iomap.c (ffffffff813259d9)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff8160c5a0)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff8182edf1)
Location: include/linux/page-flags.h:316
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8120a47c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81288099)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8129c8f3)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff8129d925)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812bcfc2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812c0ce4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8130e363)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff813369ae)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8134cbae)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81641760)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81871411)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8121775c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297c99)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812ac593)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812ad243)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812ceeb2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812d2c3c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8132138d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff8134a52e)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81364e7e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81662900)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff818a3211)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff81242fbc)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/hugetlb.c (ffffffff812cb359)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812e1633)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812e2d81)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff813056b2)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff81308a8e)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8135bac0)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff8139024b)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813abf57)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81711deb)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff819723da)
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
In kernel/events/ring_buffer.c (ffffffff8124d65c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/hugetlb.c (ffffffff812d6f92)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812ec583)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812ee1b1)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff81311412)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff8131487f)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8136a070)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff813a188b)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813bddb1)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81730028)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff819772ea)
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
In kernel/events/ring_buffer.c (ffffffff81251f99)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/memory_hotplug.c (ffffffff812c6e23)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812f3ca1)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff813174e2)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/buffer.c (ffffffff81370c80)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff813a8a2b)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813c4f71)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81713a77)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff8195b9fa)
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
In kernel/events/ring_buffer.c (ffffffff8128d839)
Location: include/linux/page-flags.h:380
Inline: True
```
```
In mm/migrate.c (ffffffff8133e641)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff81363a42)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/bootmem_info.c (ffffffff8136cb53)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/buffer.c (ffffffff813bf8d0)
Location: include/linux/page-flags.h:380
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff813f8185)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff814149a5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81790489)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81a011fa)
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
In kernel/events/ring_buffer.c (ffffffff812e25e9)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813e1e36)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/bootmem_info.c (ffffffff813eaeed)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff81e78625)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff818c8937)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
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
In kernel/events/ring_buffer.c (ffffffff8134abb9)
Location: include/linux/page-flags.h:509
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81469419)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/bootmem_info.c (ffffffff814730ed)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff8206a3e3)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81a19397)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
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
In kernel/events/ring_buffer.c (ffffffff8137bbf6)
Location: include/linux/page-flags.h:502
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149e3a8)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/bootmem_info.c (ffffffff814a785d)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff8153340f)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81a62707)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
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
In kernel/events/ring_buffer.c (ffffffff813a4e36)
Location: include/linux/page-flags.h:504
Inline: True
```
```
In mm/zsmalloc.c (ffffffff814cd4d9)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/bootmem_info.c (ffffffff814d888d)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff81568337)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/xen/grant-table.c (ffffffff81ab4f37)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
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
In kernel/events/ring_buffer.c (ffff8000102a1fc4)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffff800010336008)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffff80001034e110)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffff8000103503bc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffff8000103744a0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffff8000103788d8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffff8000103d86f8)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/crypto/crypto.c (ffff80001040aad4)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffff80001042a8cc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffff80001082cac8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffff800010af6c78)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (c04d1b70)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/migrate.c (c0551ae8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (c05602d8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/buffer.c (c05b314c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/crypto/crypto.c (c05d7e78)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (c05f4b18)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (c0bd92e8)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (c000000000353efc)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (c000000000410814)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (c00000000042e86c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (c0000000004319cc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (c00000000046657c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (c00000000046b570)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (c0000000004de948)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (c0000000005175e8)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (c00000000053c1e0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (c000000000be4df8)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffe0001d0c44)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffe000232148)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffe00023f044)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffe00024e44e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffe00025025a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffe00029239c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/crypto/crypto.c (ffffffe0002b4fa4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8a88)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9c24)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8120fdac)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290279)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a4b73)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812a5823)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812c7492)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812cb21c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8131996d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff81342b0e)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8135d45e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81628770)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81849091)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff81202b3c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281f09)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81296643)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812972f3)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812b84d2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812bc15f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8130a52d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff813337ee)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8134e0fe)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff818106f1)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8120db4c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e089)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a2983)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812a3633)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812c52a2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812c902c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8131743d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff813405de)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8135af2e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81656740)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff818986c1)
Location: include/linux/page-flags.h:349
Inline: True
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
In kernel/events/ring_buffer.c (ffffffff8121c9fc)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129de2b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812b2c13)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffffffff812b3e43)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/zsmalloc.c (ffffffff812d5d82)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/userfaultfd.c (ffffffff812d9d2d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/buffer.c (ffffffff8132902d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/crypto/crypto.c (ffffffff813538de)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8136e6ae)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/xen/grant-table.c (ffffffff81670d20)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff818b5721)
Location: include/linux/page-flags.h:349
Inline: True
```
</details>
</li>
</ul>

## Differences
