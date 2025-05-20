# Function: <code>get_tree_nodev</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf5f0)
Location: fs/super.c:1198
Inline: False
Direct callers:
  - fs/libfs.c:pseudo_fs_get_tree
```
**Symbols:**

```
ffffffff812cf5f0-ffffffff812cf608: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1920)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffff812e1920-ffffffff812e1938: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318460)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81318460-ffffffff81318516: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323770)
Location: fs/super.c:1164
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81323770-ffffffff81323826: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813298f0)
Location: fs/super.c:1166
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff813298f0-ffffffff813299a6: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376e60)
Location: fs/super.c:1166
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81376e60-ffffffff81376f16: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6100)
Location: fs/super.c:1165
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff813f6100-ffffffff813f61ab: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fcb0)
Location: fs/super.c:1166
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff8147fcb0-ffffffff8147fcd3: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b49a0)
Location: fs/super.c:1177
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff814b49a0-ffffffff814b49c3: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e60a0)
Location: fs/super.c:1283
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/proc/root.c:proc_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff814e60a0-ffffffff814e6136: get_tree_nodev (STB_GLOBAL)
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
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388ce8)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffff800010388ce8-ffff800010388d20: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0571314)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
c0571314-c0571338: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fc70)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
c00000000047fc70-c00000000047fc8c: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b21e)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffe00025b21e-ffffffe00025b252: get_tree_nodev (STB_GLOBAL)
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
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9f00)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffff812d9f00-ffffffff812d9f18: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cab80)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffff812cab80-ffffffff812cab98: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7d10)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffff812d7d10-ffffffff812d7d28: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8b50)
Location: fs/super.c:1217
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_get_tree
  - mm/shmem.c:shmem_get_tree
  - fs/libfs.c:pseudo_fs_get_tree
  - fs/ramfs/inode.c:ramfs_get_tree
```
**Symbols:**

```
ffffffff812e8b50-ffffffff812e8b68: get_tree_nodev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
