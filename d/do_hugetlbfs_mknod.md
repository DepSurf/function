# Function: <code>do_hugetlbfs_mknod</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_hugetlbfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev, bool tmpfile);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814514a5)
Location: fs/hugetlbfs/inode.c:878
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
```
**Symbols:**

```
ffffffff81450a10-ffffffff81450aa5: do_hugetlbfs_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_hugetlbfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev, bool tmpfile);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146da5a)
Location: fs/hugetlbfs/inode.c:879
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
```
**Symbols:**

```
ffffffff8146cf20-ffffffff8146cfb5: do_hugetlbfs_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_hugetlbfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev, bool tmpfile);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81472fc5)
Location: fs/hugetlbfs/inode.c:884
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
```
**Symbols:**

```
ffffffff81472610-ffffffff814726a5: do_hugetlbfs_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_hugetlbfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev, bool tmpfile);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c9ad5)
Location: fs/hugetlbfs/inode.c:885
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
```
**Symbols:**

```
ffffffff814c8e30-ffffffff814c8ec5: do_hugetlbfs_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_hugetlbfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev, bool tmpfile);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81555345)
Location: fs/hugetlbfs/inode.c:936
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mkdir
```
**Symbols:**

```
ffffffff81554590-ffffffff81554622: do_hugetlbfs_mknod (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
