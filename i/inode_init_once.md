# Function: <code>inode_init_once</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226e20)
Location: fs/inode.c:355
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81226e20-ffffffff81226eca: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f540)
Location: fs/inode.c:362
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff8124f540-ffffffff8124f5ff: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262570)
Location: fs/inode.c:364
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81262570-ffffffff8126262f: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fdc0)
Location: fs/inode.c:365
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff8126fdc0-ffffffff8126fe73: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812926f0)
Location: fs/inode.c:365
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812926f0-ffffffff812927a3: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8590)
Location: fs/inode.c:371
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812b8590-ffffffff812b86a4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd6e0)
Location: fs/inode.c:371
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812cd6e0-ffffffff812cd7f4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea480)
Location: fs/inode.c:384
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812ea480-ffffffff812ea594: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbeb0)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812fbeb0-ffffffff812fbfc4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81334b10)
Location: fs/inode.c:389
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81334b10-ffffffff81334bff: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340480)
Location: fs/inode.c:390
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81340480-ffffffff8134056f: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813469b0)
Location: fs/inode.c:390
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff813469b0-ffffffff81346a9f: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394410)
Location: fs/inode.c:394
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - block/bdev.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81394410-ffffffff813944ff: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416230)
Location: fs/inode.c:418
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - block/bdev.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81416230-ffffffff8141632d: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1590)
Location: fs/inode.c:416
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - block/bdev.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff814a1590-ffffffff814a16a2: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d68a0)
Location: fs/inode.c:416
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - block/bdev.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff814d68a0-ffffffff814d69b2: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508c90)
Location: fs/inode.c:417
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - fs/tracefs/inode.c:init_once
  - ipc/mqueue.c:init_once
  - block/bdev.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81508c90-ffffffff81508da2: inode_init_once (STB_GLOBAL)
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
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ab9d0)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffff8000103ab9d0-ffff8000103aba70: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c8fc)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
c058c8fc-c058c994: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6770)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
c0000000004a6770-c0000000004a6834: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270e7e)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffe000270e7e-ffffffe000270f1a: inode_init_once (STB_GLOBAL)
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
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4490)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812f4490-ffffffff812f45a4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e50b0)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812e50b0-ffffffff812e51c4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f22a0)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff812f22a0-ffffffff812f23b4: inode_init_once (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inode_init_once(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303870)
Location: fs/inode.c:388
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init_inode
  - fs/inode.c:init_once
  - fs/block_dev.c:init_once
  - fs/proc/inode.c:init_once
  - fs/ext4/super.c:init_once
  - fs/squashfs/super.c:init_once
  - fs/hugetlbfs/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/ecryptfs/main.c:inode_info_init_once
  - fs/fuse/inode.c:fuse_inode_init_once
  - ipc/mqueue.c:init_once
  - drivers/dax/super.c:init_once
  - net/socket.c:init_once
```
**Symbols:**

```
ffffffff81303870-ffffffff81303984: inode_init_once (STB_GLOBAL)
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
