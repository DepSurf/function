# Function: <code>mount_nodev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120fa80)
Location: fs/super.c:1118
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff8120fa80-ffffffff8120fb31: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812364d0)
Location: fs/super.c:1138
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff812364d0-ffffffff8123656a: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249180)
Location: fs/super.c:1184
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff81249180-ffffffff8124921a: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254a70)
Location: fs/super.c:1183
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff81254a70-ffffffff81254b0a: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276c00)
Location: fs/super.c:1183
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff81276c00-ffffffff81276c9c: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129d610)
Location: fs/super.c:1238
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff8129d610-ffffffff8129d6ac: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b25a0)
Location: fs/super.c:1223
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/hugetlbfs/inode.c:hugetlbfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff812b25a0-ffffffff812b263c: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf010)
Location: fs/super.c:1347
Inline: False
Direct callers:
  - init/do_mounts.c:rootfs_mount
  - kernel/bpf/inode.c:bpf_mount
  - mm/shmem.c:shmem_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ramfs/inode.c:ramfs_mount
  - fs/fuse/inode.c:fuse_mount
```
**Symbols:**

```
ffffffff812cf010-ffffffff812cf09f: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0a40)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff812e0a40-ffffffff812e0acf: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317cd0)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff81317cd0-ffffffff81317d5f: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323190)
Location: fs/super.c:1402
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff81323190-ffffffff8132321f: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329250)
Location: fs/super.c:1404
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff81329250-ffffffff813292df: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376880)
Location: fs/super.c:1404
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff81376880-ffffffff8137690f: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6050)
Location: fs/super.c:1403
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff813f6050-ffffffff813f60fe: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147f310)
Location: fs/super.c:1408
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff8147f310-ffffffff8147f3be: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3f60)
Location: fs/super.c:1425
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff814b3f60-ffffffff814b400e: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e66b0)
Location: fs/super.c:1685
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff814e66b0-ffffffff814e675e: mount_nodev (STB_GLOBAL)
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
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103876e0)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffff8000103876e0-ffff800010387794: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570840)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
c0570840-c05708e4: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047eac0)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
c00000000047eac0-c00000000047ebc0: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a74a)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffe00025a74a-ffffffe00025a7d6: mount_nodev (STB_GLOBAL)
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
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9020)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff812d9020-ffffffff812d90af: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9ca0)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff812c9ca0-ffffffff812c9d2f: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6e30)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff812d6e30-ffffffff812d6ebf: mount_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *mount_nodev(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e80a0)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff812e80a0-ffffffff812e812f: mount_nodev (STB_GLOBAL)
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
