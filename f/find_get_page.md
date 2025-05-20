# Function: <code>find_get_page</code>

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
In mm/filemap.c (ffffffff8118e1df)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/mincore.c (ffffffff811c259c)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff811d2a70)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff811d4d0d)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff811df6c9)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff811fa935)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/splice.c (ffffffff8123ea8a)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/dax.c (ffffffff8125dc96)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4cd9)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8130f825)
Location: include/linux/pagemap.h:273
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In mm/filemap.c (ffffffff811a13a1)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811c3184)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/mincore.c (ffffffff811de12e)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff811f088e)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff811f31e5)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff811fdd1b)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8121e842)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff8123d99e)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/splice.c (ffffffff81266cb5)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/hugetlbfs/inode.c (ffffffff81328769)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81343cab)
Location: include/linux/pagemap.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In mm/filemap.c (ffffffff811b0fd6)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811d3203)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/mincore.c (ffffffff811edf3e)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8120128f)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81203c7b)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff8120e819)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff81230e7c)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff81250798)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e4b1)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8135996f)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In mm/filemap.c (ffffffff811b8433)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811da880)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/mincore.c (ffffffff811f8f51)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8120c11d)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8120f266)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff8121a11d)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8123c6dc)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff8125c924)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813530b8)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8136e15b)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In mm/filemap.c (ffffffff811ccb9d)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811f0613)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8121128d)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff812257e1)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8122aaaf)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff812351ed)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8125c363)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff8127ec47)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff81377c25)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81392d38)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff811d0d01)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/filemap.c (ffffffff811edc9d)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81211d83)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff81231dc9)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff81247d81)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8124bd56)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81257fd1)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8127fc48)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812a55d7)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6608)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff813c299a)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In kernel/bpf/stackmap.c (ffffffff811e082d)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/filemap.c (ffffffff811ff253)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81223c20)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff81245599)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8125c34e)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8125f8ac)
Location: include/linux/pagemap.h:269
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126c6b0)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812945ba)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812ba744)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf3e8)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff813dc489)
Location: include/linux/pagemap.h:269
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In kernel/bpf/stackmap.c (ffffffff811f643c)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/filemap.c (ffffffff812162b0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123544d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8125764b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127751f)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8127bbb0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81287a3c)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812b08a9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812d734e)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9c6d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814072d2)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff812033fa)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8121aab6)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81223bc0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8124368d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff81265b9b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff81287000)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128b690)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129764b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812c2309)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812e8eae)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff81403d0d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814220c9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff8122b171)
Location: include/linux/pagemap.h:295
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81247512)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81252b9e)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8126f84d)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff81295edc)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff812b958d)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812be570)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812cae0f)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812f925a)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff8132155e)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff81451b61)
Location: include/linux/pagemap.h:295
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8146f76f)
Location: include/linux/pagemap.h:295
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
In kernel/bpf/stackmap.c (ffffffff812330a5)
Location: include/linux/pagemap.h:332
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81251b88)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8125d76e)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8127abbd)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff812c5004)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812ca13a)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812d6a2f)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8130186e)
Location: include/linux/pagemap.h:332
Inline: True
```
```
In fs/namei.c (ffffffff8132cafe)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e0eb)
Location: include/linux/pagemap.h:332
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81489fa1)
Location: include/linux/pagemap.h:332
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
In kernel/events/uprobes.c (ffffffff81255971)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81260531)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8127fd36)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff812cbcb4)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812d0c26)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812ddc4f)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
```
```
In mm/memcontrol.c (ffffffff81308064)
Location: include/linux/pagemap.h:348
Inline: True
```
```
In fs/namei.c (ffffffff813326cc)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff8147352d)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8148faef)
Location: include/linux/pagemap.h:348
Inline: True
```
```
In lib/buildid.c (ffffffff815efeae)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/events/uprobes.c (ffffffff81291621)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8129cf21)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812be046)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/swap_state.c (ffffffff81310e37)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81316303)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81324e20)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
```
```
In mm/memcontrol.c (ffffffff813521ee)
Location: include/linux/pagemap.h:348
Inline: True
```
```
In fs/namei.c (ffffffff8137fe5c)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca121)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814e755f)
Location: include/linux/pagemap.h:348
Inline: True
```
```
In lib/buildid.c (ffffffff8165d14e)
Location: include/linux/pagemap.h:348
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/events/uprobes.c (ffffffff812e6c5f)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8131a916)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/swap_state.c (ffffffff8137bcc9)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81381446)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81393480)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
```
```
In mm/memcontrol.c (ffffffff813ce6fb)
Location: include/linux/pagemap.h:562
Inline: True
```
```
In fs/namei.c (ffffffff814007d6)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff81555e40)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81575129)
Location: include/linux/pagemap.h:562
Inline: True
```
```
In lib/buildid.c (ffffffff8177659e)
Location: include/linux/pagemap.h:562
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/events/uprobes.c (ffffffff8135074e)
Location: include/linux/pagemap.h:559
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/hugetlb.c (ffffffff81411c1f)
Location: include/linux/pagemap.h:559
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8145015b)
Location: include/linux/pagemap.h:559
Inline: True
```
```
In fs/namei.c (ffffffff8148b256)
Location: include/linux/pagemap.h:559
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7538)
Location: include/linux/pagemap.h:559
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8161a2f9)
Location: include/linux/pagemap.h:559
Inline: True
```
```
In lib/buildid.c (ffffffff8201efeb)
Location: include/linux/pagemap.h:559
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/events/uprobes.c (ffffffff8138190d)
Location: include/linux/pagemap.h:586
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memcontrol.c (ffffffff81485bbb)
Location: include/linux/pagemap.h:586
Inline: True
```
```
In fs/namei.c (ffffffff814c0b82)
Location: include/linux/pagemap.h:586
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/squashfs/block.c (ffffffff8162416a)
Location: include/linux/pagemap.h:586
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/fuse/dev.c (ffffffff81652614)
Location: include/linux/pagemap.h:586
Inline: True
```
```
In lib/buildid.c (ffffffff8209effe)
Location: include/linux/pagemap.h:586
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/events/uprobes.c (ffffffff813aac9f)
Location: include/linux/pagemap.h:704
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memcontrol.c (ffffffff814b456b)
Location: include/linux/pagemap.h:704
Inline: True
```
```
In fs/namei.c (ffffffff814f2fa2)
Location: include/linux/pagemap.h:704
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/squashfs/block.c (ffffffff8165d20a)
Location: include/linux/pagemap.h:704
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/fuse/dev.c (ffffffff8168bc24)
Location: include/linux/pagemap.h:704
Inline: True
```
```
In lib/buildid.c (ffffffff82176ffe)
Location: include/linux/pagemap.h:704
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In kernel/bpf/stackmap.c (ffff80001028bb6c)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffff8000102a5ebc)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffff8000102b15dc)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffff8000102d5964)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffff8000102fcd80)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffff800010321af4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffff800010326954)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffff8000103356a0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffff800010363dd4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffff800010393a20)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffff8000104e24b4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffff800010504db0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (c04bb220)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (c04d4ea4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04ddf38)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c04fdaf8)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/mincore.c (c051c484)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (c053a224)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c053e12c)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/memcontrol.c (c0556108)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (c05797f4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/fuse/dev.c (c06bf6ec)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_retrieve
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
In kernel/bpf/stackmap.c (c000000000337bb4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (c000000000358f24)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c000000000366e18)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c000000000395860)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (c0000000003c7d48)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (c0000000003f72c0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c0000000003fd390)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (c00000000040f714)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (c000000000450eb0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (c00000000048ab30)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (c00000000061f520)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (c00000000064a010)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffe0001bf6a6)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In mm/filemap.c (ffffffe0001d6cf0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffe0001f13d6)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In mm/mincore.c (ffffffe00020b998)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffe000222c66)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffe000226af4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffe000231afe)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffe000241cac)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffe000261430)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffe000355fa2)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffe0003718be)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff811fba1a)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81213106)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121c210)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123bcdd)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8125e1eb)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127f650)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81283c70)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128fc2b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812ba8e9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812e148e)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc2ed)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8141a6a9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff811ee765)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81205e76)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8120f400)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122ecdd)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8125067b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff81271470)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81275af9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812818eb)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812abaa7)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812d20ce)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecd6d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8140b129)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff811f97ea)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81210ea6)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81219fb0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81239a7d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8125bf8b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127d3f0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81281a80)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128da3b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812b86f9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812df29e)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff813f966d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81416849)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In kernel/bpf/stackmap.c (ffffffff8120828a)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8121fdeb)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff812290a0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8124916d)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mincore.c (ffffffff8126b97b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8128cfbf)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81291791)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129d7f4)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812c8d39)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/namei.c (ffffffff812f068e)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f2c8)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8142d5a9)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
</details>
</li>
</ul>

## Differences
