# Function: <code>efivarfs_fileattr_get</code>

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
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a8b60)
Location: fs/efivarfs/inode.c:147
Inline: False
```
**Symbols:**

```
ffffffff814a8b60-ffffffff814a8b84: efivarfs_fileattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81500e90)
Location: fs/efivarfs/inode.c:147
Inline: False
```
**Symbols:**

```
ffffffff81500e90-ffffffff81500eb4: efivarfs_fileattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff815921b0)
Location: fs/efivarfs/inode.c:147
Inline: False
```
**Symbols:**

```
ffffffff815921b0-ffffffff815921dd: efivarfs_fileattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81639ab0)
Location: fs/efivarfs/inode.c:151
Inline: False
```
**Symbols:**

```
ffffffff81639ab0-ffffffff81639add: efivarfs_fileattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81671f10)
Location: fs/efivarfs/inode.c:151
Inline: False
```
**Symbols:**

```
ffffffff81671f10-ffffffff81671f3d: efivarfs_fileattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivarfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff816adef0)
Location: fs/efivarfs/inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff816adef0-ffffffff816adf1d: efivarfs_fileattr_get (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
