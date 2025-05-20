# Function: <code>configfs_get_link</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *configfs_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff812e1000)
Location: fs/configfs/symlink.c:281
Inline: True
```
**Symbols:**

```
ffffffff812e1000-ffffffff812e134b: configfs_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *configfs_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81305990)
Location: fs/configfs/symlink.c:281
Inline: True
```
**Symbols:**

```
ffffffff81305990-ffffffff81305c80: configfs_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *configfs_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81333980)
Location: fs/configfs/symlink.c:281
Inline: True
```
**Symbols:**

```
ffffffff81333980-ffffffff81333c71: configfs_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *configfs_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8134ad10)
Location: fs/configfs/symlink.c:281
Inline: True
```
**Symbols:**

```
ffffffff8134ad10-ffffffff8134afef: configfs_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *configfs_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813736a0)
Location: fs/configfs/symlink.c:267
Inline: True
```
**Symbols:**

```
ffffffff813736a0-ffffffff81373963: configfs_get_link (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
</ul>
