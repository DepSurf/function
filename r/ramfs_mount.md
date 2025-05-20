# Function: <code>ramfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff812f3200)
Location: fs/ramfs/inode.c:239
Inline: False
```
**Symbols:**

```
ffffffff812f3200-ffffffff812f321a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81326980)
Location: fs/ramfs/inode.c:240
Inline: False
```
**Symbols:**

```
ffffffff81326980-ffffffff8132699a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8133c730)
Location: fs/ramfs/inode.c:240
Inline: False
```
**Symbols:**

```
ffffffff8133c730-ffffffff8133c74a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81351260)
Location: fs/ramfs/inode.c:250
Inline: False
```
**Symbols:**

```
ffffffff81351260-ffffffff8135127a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81375d60)
Location: fs/ramfs/inode.c:250
Inline: False
```
**Symbols:**

```
ffffffff81375d60-ffffffff81375d7a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813a4780)
Location: fs/ramfs/inode.c:250
Inline: False
```
**Symbols:**

```
ffffffff813a4780-ffffffff813a479a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813bd580)
Location: fs/ramfs/inode.c:250
Inline: False
```
**Symbols:**

```
ffffffff813bd580-ffffffff813bd59a: ramfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *ramfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813e7e10)
Location: fs/ramfs/inode.c:250
Inline: False
```
**Symbols:**

```
ffffffff813e7e10-ffffffff813e7e2a: ramfs_mount (STB_GLOBAL)
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
</ul>
