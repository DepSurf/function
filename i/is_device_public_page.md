# Function: <code>is_device_public_page</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/swap.c (ffffffff811e0899)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/gup.c (ffffffff8120745f)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120a601)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:_vm_normal_page
```
```
In mm/mincore.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/migrate.c (ffffffff8124c7aa)
Location: include/linux/memremap.h:169
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/memremap.h:169
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/memremap.h:169
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
In mm/swap.c (ffffffff8120210c)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff81228194)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122b0e6)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
```
```
In mm/migrate.c (ffffffff81270232)
Location: include/linux/mm.h:886
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:886
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
In mm/swap.c (ffffffff81214a8c)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/gup.c (ffffffff8123b9b5)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123e4a6)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
```
```
In mm/migrate.c (ffffffff812848e4)
Location: include/linux/mm.h:919
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:919
Inline: True
```
</details>
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
