# Function: <code>inode_nohighmem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f100)
Location: fs/inode.c:2050
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
**Symbols:**

```
ffffffff8124f100-ffffffff8124f123: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262110)
Location: fs/inode.c:2100
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
**Symbols:**

```
ffffffff81262110-ffffffff81262126: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126f9c0)
Location: fs/inode.c:2090
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
**Symbols:**

```
ffffffff8126f9c0-ffffffff8126f9d6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812922e0)
Location: fs/inode.c:2103
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
**Symbols:**

```
ffffffff812922e0-ffffffff812922f9: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b81b0)
Location: fs/inode.c:2101
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
**Symbols:**

```
ffffffff812b81b0-ffffffff812b81c9: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd300)
Location: fs/inode.c:2108
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812cd300-ffffffff812cd316: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e9f40)
Location: fs/inode.c:2140
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812e9f40-ffffffff812e9f56: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fb9d0)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812fb9d0-ffffffff812fb9e6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813347d0)
Location: fs/inode.c:2235
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff813347d0-ffffffff813347e6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340120)
Location: fs/inode.c:2236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81340120-ffffffff81340136: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346640)
Location: fs/inode.c:2262
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81346640-ffffffff81346656: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394060)
Location: fs/inode.c:2267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81394060-ffffffff81394076: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81415c50)
Location: fs/inode.c:2348
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81415c50-ffffffff81415c6e: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1080)
Location: fs/inode.c:2397
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff814a1080-ffffffff814a109e: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6390)
Location: fs/inode.c:2442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff814d6390-ffffffff814d63ae: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508760)
Location: fs/inode.c:2445
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81508760-ffffffff8150877e: inode_nohighmem (STB_GLOBAL)
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
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ab808)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffff8000103ab808-ffff8000103ab83c: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c298)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
c058c298-c058c2c0: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a61a0)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
c0000000004a61a0-c0000000004a61bc: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270a22)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffe000270a22-ffffffe000270a4e: inode_nohighmem (STB_GLOBAL)
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
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3fb0)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812f3fb0-ffffffff812f3fc6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e4be0)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812e4be0-ffffffff812e4bf6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f1dc0)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff812f1dc0-ffffffff812f1dd6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inode_nohighmem(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303390)
Location: fs/inode.c:2151
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_symlink
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/fuse/dir.c:fuse_init_symlink
```
**Symbols:**

```
ffffffff81303390-ffffffff813033a6: inode_nohighmem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
