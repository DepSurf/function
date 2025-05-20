# Function: <code>hugetlbfs_tmpfile</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814514a0)
Location: fs/hugetlbfs/inode.c:920
Inline: False
```
**Symbols:**

```
ffffffff814514a0-ffffffff81451508: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146da40)
Location: fs/hugetlbfs/inode.c:921
Inline: False
```
**Symbols:**

```
ffffffff8146da40-ffffffff8146daa8: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81472fb0)
Location: fs/hugetlbfs/inode.c:930
Inline: False
```
**Symbols:**

```
ffffffff81472fb0-ffffffff81473015: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c9ac0)
Location: fs/hugetlbfs/inode.c:931
Inline: False
```
**Symbols:**

```
ffffffff814c9ac0-ffffffff814c9b25: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81555330)
Location: fs/hugetlbfs/inode.c:982
Inline: False
```
**Symbols:**

```
ffffffff81555330-ffffffff815553a1: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct user_namespace *mnt_userns, struct inode *dir, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff815f5f10)
Location: fs/hugetlbfs/inode.c:1053
Inline: False
```
**Symbols:**

```
ffffffff815f5f10-ffffffff815f5f8e: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct mnt_idmap *idmap, struct inode *dir, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8162de90)
Location: fs/hugetlbfs/inode.c:1048
Inline: False
```
**Symbols:**

```
ffffffff8162de90-ffffffff8162df11: hugetlbfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hugetlbfs_tmpfile(struct mnt_idmap *idmap, struct inode *dir, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81667360)
Location: fs/hugetlbfs/inode.c:1079
Inline: False
```
**Symbols:**

```
ffffffff81667360-ffffffff816673d6: hugetlbfs_tmpfile (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, dentry, mode</code> ➡️ <code>mnt_userns, dir, dentry, mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
