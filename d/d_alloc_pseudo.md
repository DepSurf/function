# Function: <code>d_alloc_pseudo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812259e0)
Location: fs/dcache.c:1645
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:SyS_io_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812259e0-ffffffff812259f0: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124db20)
Location: fs/dcache.c:1682
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/nsfs.c:ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8124db20-ffffffff8124db30: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260c00)
Location: fs/dcache.c:1691
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/pipe.c:create_pipe_files
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81260c00-ffffffff81260c10: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e3d0)
Location: fs/dcache.c:1721
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8126e3d0-ffffffff8126e3e0: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290cf0)
Location: fs/dcache.c:1733
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/nsfs.c:__ns_get_path
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81290cf0-ffffffff81290d00: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7640)
Location: fs/dcache.c:1741
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812b7640-ffffffff812b7650: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc7a0)
Location: fs/dcache.c:1744
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812cc7a0-ffffffff812cc7b0: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e93d0)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812e93d0-ffffffff812e93eb: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812faf70)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812faf70-ffffffff812faf8b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333c50)
Location: fs/dcache.c:1837
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81333c50-ffffffff81333c6b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f5d0)
Location: fs/dcache.c:1844
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff8133f5d0-ffffffff8133f5eb: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345a50)
Location: fs/dcache.c:1871
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81345a50-ffffffff81345a6b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81393660)
Location: fs/dcache.c:1872
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81393660-ffffffff8139367b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414dc0)
Location: fs/dcache.c:1897
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81414dc0-ffffffff81414de3: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a0300)
Location: fs/dcache.c:1897
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff814a0300-ffffffff814a0323: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d5620)
Location: fs/dcache.c:1897
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff814d5620-ffffffff814d5643: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81507a40)
Location: fs/dcache.c:1751
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81507a40-ffffffff81507a9e: d_alloc_pseudo (STB_GLOBAL)
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
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa2c8)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffff8000103aa2c8-ffff8000103aa30c: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b27c)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
c058b27c-c058b2a8: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a5180)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
c0000000004a5180-c0000000004a51c4: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00027003a)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffe00027003a-ffffffe000270078: d_alloc_pseudo (STB_GLOBAL)
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
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3550)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812f3550-ffffffff812f356b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4180)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812e4180-ffffffff812e419b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1360)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff812f1360-ffffffff812f137b: d_alloc_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_alloc_pseudo(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302520)
Location: fs/dcache.c:1816
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
```
**Symbols:**

```
ffffffff81302520-ffffffff8130253b: d_alloc_pseudo (STB_GLOBAL)
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
