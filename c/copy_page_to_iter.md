# Function: <code>copy_page_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fdbb0)
Location: lib/iov_iter.c:449
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff813fdbb0-ffffffff813fdc41: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81444cf0)
Location: lib/iov_iter.c:404
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff81444cf0-ffffffff81444d7a: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81463550)
Location: lib/iov_iter.c:642
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff81463550-ffffffff814636fb: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814674a0)
Location: lib/iov_iter.c:697
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff814674a0-ffffffff81467740: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814935a0)
Location: lib/iov_iter.c:699
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff814935a0-ffffffff8149388b: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c89c0)
Location: lib/iov_iter.c:829
Inline: True
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/core/datagram.c:skb_copy_datagram_iter
```
**Symbols:**

```
ffffffff814c89c0-ffffffff814c8cc3: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dd060)
Location: lib/iov_iter.c:873
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff814dd060-ffffffff814dd363: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81509908)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8150ae38-ffffffff8150ae4a: copy_page_to_iter.cold (STB_LOCAL)
ffffffff81509790-ffffffff81509a98: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81526bb0)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81526bb0-ffffffff81526ec4: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158b930)
Location: lib/iov_iter.c:908
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/process_vm_access.c:process_vm_rw_single_vec
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_to_iter
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8158b930-ffffffff8158ba5f: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a74b0)
Location: lib/iov_iter.c:915
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_to_iter
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff815a74b0-ffffffff815a75df: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b13b0)
Location: lib/iov_iter.c:979
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff815b13b0-ffffffff815b17ec: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:826
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff81cda970-ffffffff81cda989: copy_page_to_iter.cold (STB_LOCAL)
ffffffff81618ea0-ffffffff81619291: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e5b90)
Location: lib/iov_iter.c:878
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff816e5b90-ffffffff816e5f61: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:712
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff820781fd-ffffffff82078212: copy_page_to_iter.cold (STB_LOCAL)
ffffffff817d42b0-ffffffff817d44a8: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81811d01)
Location: lib/iov_iter.c:468
Inline: True
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff820f8542-ffffffff820f8578: copy_page_to_iter.cold (STB_LOCAL)
ffffffff81811cb0-ffffffff81811e18: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81858af1)
Location: lib/iov_iter.c:349
Inline: True
Direct callers:
  - mm/filemap.c:filemap_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:blk_rq_unmap_user
  - net/core/skmsg.c:sk_msg_recvmsg
```
**Symbols:**

```
ffffffff821d62e0-ffffffff821d6313: copy_page_to_iter.cold (STB_LOCAL)
ffffffff81858aa0-ffffffff81858c08: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff8000106312d0)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffff8000106312d0-ffff800010631634: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d7704)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
c07d7704-c07d7994: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d51d0)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
c0000000007d51d0-c0000000007d566c: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045fcca)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe00045fcca-ffffffe00045ffa2: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151f190)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8151f190-ffffffff8151f4a4: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150f480)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8150f480-ffffffff8150f794: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151b220)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8151b220-ffffffff8151b534: copy_page_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_to_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81534a50)
Location: lib/iov_iter.c:887
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_buffered_read
  - mm/shmem.c:shmem_file_read_iter
  - fs/pipe.c:pipe_read
  - fs/splice.c:pipe_to_user
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_uncopy_user
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81534a50-ffffffff81534d73: copy_page_to_iter (STB_GLOBAL)
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
