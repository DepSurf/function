# Function: <code>__kcsan_check_access</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:148
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: False
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:142
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:142
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:148
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:148
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:148
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: False
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/secretmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/block.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
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
In init/do_mounts.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: False
```
```
In mm/madvise.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/read_metadata.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/block.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/fops.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/stackdepot.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
```
```
In lib/buildid.c (0)
Location: include/linux/kcsan-checks.h:189
Inline: True
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
