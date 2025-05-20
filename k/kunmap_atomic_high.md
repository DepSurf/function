# Function: <code>kunmap_atomic_high</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/page_poison.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/squashfs/page_actor.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In crypto/scatterwalk.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In block/t10-pi.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/highmem.h:162
Inline: True
```
</details>
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
