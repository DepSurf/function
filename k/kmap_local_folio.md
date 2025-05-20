# Function: <code>kmap_local_folio</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81442001)
Location: include/linux/highmem-internal.h:185
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8148a3cb)
Location: include/linux/highmem-internal.h:185
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In lib/iov_iter.c (ffffffff816e6c16)
Location: include/linux/highmem-internal.h:185
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/shmem.c (ffffffff81390660)
Location: include/linux/highmem-internal.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In fs/remap_range.c (ffffffff814d0ae7)
Location: include/linux/highmem-internal.h:185
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151ddb8)
Location: include/linux/highmem-internal.h:185
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In lib/iov_iter.c (ffffffff817d6594)
Location: include/linux/highmem-internal.h:185
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/shmem.c (ffffffff813c2fab)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/userfaultfd.c (ffffffff814a1c62)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/remap_range.c (ffffffff815071e7)
Location: include/linux/highmem-internal.h:188
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153e559)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff81555f54)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/ext4/inline.c (ffffffff815adbaa)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/verity.c (ffffffff81612292)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In lib/iov_iter.c (ffffffff81813c2a)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/shmem.c (ffffffff813edaea)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/userfaultfd.c (ffffffff814d1458)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/remap_range.c (ffffffff8153c550)
Location: include/linux/highmem-internal.h:188
Inline: True
```
```
In fs/verity/verify.c (ffffffff81573af9)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8158c448)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/ext4/inline.c (ffffffff815e696a)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/verity.c (ffffffff8164b27c)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164c578)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81650110)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8165c979)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In lib/iov_iter.c (ffffffff81858881)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81ece781)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddafd)
Location: include/linux/highmem-internal.h:188
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
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
