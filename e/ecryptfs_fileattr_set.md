# Function: <code>ecryptfs_fileattr_set</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81480f40)
Location: fs/ecryptfs/inode.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81480f40-ffffffff81480f82: ecryptfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff814d8840)
Location: fs/ecryptfs/inode.c:1111
Inline: False
```
**Symbols:**

```
ffffffff814d8840-ffffffff814d8882: ecryptfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81566070)
Location: fs/ecryptfs/inode.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81566070-ffffffff815660bc: ecryptfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81609410)
Location: fs/ecryptfs/inode.c:1113
Inline: False
```
**Symbols:**

```
ffffffff81609410-ffffffff8160945c: ecryptfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff816412d0)
Location: fs/ecryptfs/inode.c:1113
Inline: False
```
**Symbols:**

```
ffffffff816412d0-ffffffff8164131c: ecryptfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167a890)
Location: fs/ecryptfs/inode.c:1132
Inline: False
```
**Symbols:**

```
ffffffff8167a890-ffffffff8167a8df: ecryptfs_fileattr_set (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
