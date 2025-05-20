# Function: <code>clear_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226ee0)
Location: fs/inode.c:488
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
```
**Symbols:**

```
ffffffff81226ee0-ffffffff81226f61: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f610)
Location: fs/inode.c:496
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
```
**Symbols:**

```
ffffffff8124f610-ffffffff8124f6a9: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262640)
Location: fs/inode.c:498
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
```
**Symbols:**

```
ffffffff81262640-ffffffff812626d9: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fee0)
Location: fs/inode.c:498
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff8126fee0-ffffffff8126ff79: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292810)
Location: fs/inode.c:498
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff81292810-ffffffff812928a9: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8450)
Location: fs/inode.c:504
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff812b8450-ffffffff812b84e4: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd5a0)
Location: fs/inode.c:504
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff812cd5a0-ffffffff812cd634: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea290)
Location: fs/inode.c:517
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff812ea290-ffffffff812ea324: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbd70)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff812fbd70-ffffffff812fbe04: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335fa0)
Location: fs/inode.c:522
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81335fa0-ffffffff81336034: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341930)
Location: fs/inode.c:523
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81341930-ffffffff813419c4: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347c70)
Location: fs/inode.c:523
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81347c70-ffffffff81347cf8: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395880)
Location: fs/inode.c:527
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff81395880-ffffffff81395908: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814161a0)
Location: fs/inode.c:604
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff814161a0-ffffffff81416229: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a14f0)
Location: fs/inode.c:603
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff814a14f0-ffffffff814a1579: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6800)
Location: fs/inode.c:603
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff814d6800-ffffffff814d6889: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508bf0)
Location: fs/inode.c:604
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff81508bf0-ffffffff81508c79: clear_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103adba0)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffff8000103adba0-ffff8000103adc90: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c5ac)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
c058c5ac-c058c65c: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6900)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
c0000000004a6900-c0000000004a69f0: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002724dc)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffe0002724dc-ffffffe000272590: clear_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4350)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff812f4350-ffffffff812f43e4: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e4f80)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff812e4f80-ffffffff812e500e: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2160)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff812f2160-ffffffff812f21f4: clear_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303740)
Location: fs/inode.c:521
Inline: False
Direct callers:
  - mm/shmem.c:shmem_evict_inode
  - fs/inode.c:evict
  - fs/nsfs.c:nsfs_evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/super.c:ext4_clear_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/pstore/inode.c:pstore_evict_inode
  - fs/efivarfs/super.c:efivarfs_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
```
**Symbols:**

```
ffffffff81303740-ffffffff813037cb: clear_inode (STB_GLOBAL)
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
