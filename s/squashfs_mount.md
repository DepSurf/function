# Function: <code>squashfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81323e00)
Location: fs/squashfs/super.c:400
Inline: False
```
**Symbols:**

```
ffffffff81323e00-ffffffff81323e17: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81339c90)
Location: fs/squashfs/super.c:400
Inline: False
```
**Symbols:**

```
ffffffff81339c90-ffffffff81339ca7: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff8134e960)
Location: fs/squashfs/super.c:400
Inline: False
```
**Symbols:**

```
ffffffff8134e960-ffffffff8134e977: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff81373010)
Location: fs/squashfs/super.c:400
Inline: False
```
**Symbols:**

```
ffffffff81373010-ffffffff81373027: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff813a1960)
Location: fs/squashfs/super.c:401
Inline: False
```
**Symbols:**

```
ffffffff813a1960-ffffffff813a1977: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff813ba740)
Location: fs/squashfs/super.c:401
Inline: False
```
**Symbols:**

```
ffffffff813ba740-ffffffff813ba757: squashfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *squashfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/super.c (ffffffff813e5020)
Location: fs/squashfs/super.c:388
Inline: False
```
**Symbols:**

```
ffffffff813e5020-ffffffff813e5037: squashfs_mount (STB_LOCAL)
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
