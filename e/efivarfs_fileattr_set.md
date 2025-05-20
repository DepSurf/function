# Function: <code>efivarfs_fileattr_set</code>

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
int efivarfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a8b90)
Location: fs/efivarfs/inode.c:162
Inline: False
```
**Symbols:**

```
ffffffff814a8b90-ffffffff814a8bf0: efivarfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivarfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81500ec0)
Location: fs/efivarfs/inode.c:162
Inline: False
```
**Symbols:**

```
ffffffff81500ec0-ffffffff81500f20: efivarfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivarfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff815921e0)
Location: fs/efivarfs/inode.c:162
Inline: False
```
**Symbols:**

```
ffffffff815921e0-ffffffff8159226d: efivarfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivarfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81639af0)
Location: fs/efivarfs/inode.c:166
Inline: False
```
**Symbols:**

```
ffffffff81639af0-ffffffff81639b7d: efivarfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivarfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81671f50)
Location: fs/efivarfs/inode.c:166
Inline: False
```
**Symbols:**

```
ffffffff81671f50-ffffffff81671fdd: efivarfs_fileattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivarfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff816adf30)
Location: fs/efivarfs/inode.c:171
Inline: False
```
**Symbols:**

```
ffffffff816adf30-ffffffff816adfbd: efivarfs_fileattr_set (STB_LOCAL)
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
