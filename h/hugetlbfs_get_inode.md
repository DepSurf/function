# Function: <code>hugetlbfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff812f4680)
Location: fs/hugetlbfs/inode.c:719
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff812f4680-ffffffff812f4800: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813278e0)
Location: fs/hugetlbfs/inode.c:725
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813278e0-ffffffff81327a46: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133d630)
Location: fs/hugetlbfs/inode.c:723
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff8133d630-ffffffff8133d78e: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81351a30)
Location: fs/hugetlbfs/inode.c:729
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff81351a30-ffffffff81351b6d: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81376ed0)
Location: fs/hugetlbfs/inode.c:723
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff81376ed0-ffffffff8137700e: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a5690)
Location: fs/hugetlbfs/inode.c:741
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813a5690-ffffffff813a57d6: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813be500)
Location: fs/hugetlbfs/inode.c:739
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813be500-ffffffff813be646: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e8d60)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813e8d60-ffffffff813e8ed7: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81402e00)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff81402e00-ffffffff81402f77: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81450870)
Location: fs/hugetlbfs/inode.c:817
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
**Symbols:**

```
ffffffff81450870-ffffffff81450a01: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146cd80)
Location: fs/hugetlbfs/inode.c:818
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
**Symbols:**

```
ffffffff8146cd80-ffffffff8146cf11: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81472470)
Location: fs/hugetlbfs/inode.c:823
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
**Symbols:**

```
ffffffff81472470-ffffffff81472608: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c8c90)
Location: fs/hugetlbfs/inode.c:824
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
**Symbols:**

```
ffffffff814c8c90-ffffffff814c8e2b: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff815543f0)
Location: fs/hugetlbfs/inode.c:875
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
```
**Symbols:**

```
ffffffff815543f0-ffffffff8155458e: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff815f5d60)
Location: fs/hugetlbfs/inode.c:961
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff815f5d60-ffffffff815f5efe: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8162dc50)
Location: fs/hugetlbfs/inode.c:956
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff8162dc50-ffffffff8162de76: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81667160)
Location: fs/hugetlbfs/inode.c:987
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff81667160-ffffffff8166734d: hugetlbfs_get_inode (STB_LOCAL)
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
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e09d8)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffff8000104e09d8-ffff8000104e0b98: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061d4e0)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
c00000000061d4e0-c00000000061d794: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe000354c40)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffe000354c40-ffffffe000354d8e: hugetlbfs_get_inode (STB_LOCAL)
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
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813fb3e0)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813fb3e0-ffffffff813fb557: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813ebe60)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813ebe60-ffffffff813ebfd7: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f8760)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff813f8760-ffffffff813f88d7: hugetlbfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *hugetlbfs_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140e560)
Location: fs/hugetlbfs/inode.c:757
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
**Symbols:**

```
ffffffff8140e560-ffffffff8140e6d7: hugetlbfs_get_inode (STB_LOCAL)
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
