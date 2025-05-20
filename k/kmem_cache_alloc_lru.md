# Function: <code>kmem_cache_alloc_lru</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kmem_cache_alloc_lru(struct kmem_cache *s, struct list_lru *lru, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813aa0b0)
Location: mm/slub.c:3272
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_inode
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/proc/inode.c:proc_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - block/bdev.c:bdev_alloc_inode
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:xas_nomem
  - drivers/dax/super.c:dax_alloc_inode
  - net/socket.c:sock_alloc_inode
```
**Symbols:**

```
ffffffff813aa0b0-ffffffff813aa347: kmem_cache_alloc_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kmem_cache_alloc_lru(struct kmem_cache *s, struct list_lru *lru, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142af20)
Location: mm/slub.c:3480
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_inode
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/proc/inode.c:proc_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - block/bdev.c:bdev_alloc_inode
  - drivers/dax/super.c:dax_alloc_inode
  - net/socket.c:sock_alloc_inode
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:xas_nomem
```
**Symbols:**

```
ffffffff8142af20-ffffffff8142b1d5: kmem_cache_alloc_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kmem_cache_alloc_lru(struct kmem_cache *s, struct list_lru *lru, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81460450)
Location: mm/slub.c:3498
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_inode
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/proc/inode.c:proc_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - block/bdev.c:bdev_alloc_inode
  - drivers/dax/super.c:dax_alloc_inode
  - net/socket.c:sock_alloc_inode
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:xas_nomem
```
**Symbols:**

```
ffffffff81460450-ffffffff8146072f: kmem_cache_alloc_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_lru(struct kmem_cache *s, struct list_lru *lru, gfp_t gfpflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145c300)
Location: mm/slub.c:3876
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_inode
  - fs/dcache.c:__d_alloc
  - fs/inode.c:alloc_inode
  - fs/proc/inode.c:proc_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/squashfs/super.c:squashfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/fat/inode.c:fat_alloc_inode
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_alloc_inode
  - block/bdev.c:bdev_alloc_inode
  - drivers/dax/super.c:dax_alloc_inode
  - net/socket.c:sock_alloc_inode
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:xas_nomem
```
**Symbols:**

```
ffffffff8145c300-ffffffff8145c633: kmem_cache_alloc_lru (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
