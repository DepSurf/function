# Function: <code>inode_newsize_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812292f0)
Location: fs/attr.c:141
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:inode_change_ok
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff812292f0-ffffffff8122935a: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81251a20)
Location: fs/attr.c:117
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:inode_change_ok
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff81251a20-ffffffff81251a8a: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81264bf0)
Location: fs/attr.c:130
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff81264bf0-ffffffff81264c5a: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81272420)
Location: fs/attr.c:131
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff81272420-ffffffff8127248a: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81294d40)
Location: fs/attr.c:132
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff81294d40-ffffffff81294dab: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812baf00)
Location: fs/attr.c:134
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff812baf00-ffffffff812baf6b: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812d00f0)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
```
**Symbols:**

```
ffffffff812d00f0-ffffffff812d015b: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812ed110)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812ed110-ffffffff812ed17a: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812feb70)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812feb70-ffffffff812febda: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81337c70)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81337c70-ffffffff81337cd4: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff813435d0)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813435d0-ffffffff81343634: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff813498d0)
Location: fs/attr.c:171
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813498d0-ffffffff81349937: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81397620)
Location: fs/attr.c:171
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81397620-ffffffff81397687: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81419810)
Location: fs/attr.c:185
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81419810-ffffffff814198b1: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a52e0)
Location: fs/attr.c:247
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff814a52e0-ffffffff814a5381: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814da710)
Location: fs/attr.c:248
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff814da710-ffffffff814da7b1: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150ccb0)
Location: fs/attr.c:248
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8150ccb0-ffffffff8150cd51: inode_newsize_ok (STB_GLOBAL)
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
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffff8000103b0040)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffff8000103b0040-ffff8000103b00d0: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/attr.c (c058f974)
Location: fs/attr.c:135
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
c058f880-c058f8fc: inode_newsize_ok.part.0 (STB_LOCAL)
c058f8fc-c058f944: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (c0000000004ab710)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/buffer.c:generic_cont_expand_simple
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
c0000000004ab710-c0000000004ab7bc: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffe0002744a4)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffe0002744a4-ffffffe000274510: inode_newsize_ok (STB_GLOBAL)
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
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f7150)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812f7150-ffffffff812f71ba: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812e7d70)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812e7d70-ffffffff812e7dda: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f4f60)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812f4f60-ffffffff812f4fca: inode_newsize_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int inode_newsize_ok(const struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff813060f0)
Location: fs/attr.c:135
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - fs/attr.c:setattr_prepare
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813060f0-ffffffff8130615a: inode_newsize_ok (STB_GLOBAL)
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
