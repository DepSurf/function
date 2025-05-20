# Function: <code>configfs_do_mount</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *configfs_do_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff812e1830)
Location: fs/configfs/mount.c:105
Inline: False
```
**Symbols:**

```
ffffffff812e1830-ffffffff812e184a: configfs_do_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *configfs_do_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81306180)
Location: fs/configfs/mount.c:105
Inline: False
```
**Symbols:**

```
ffffffff81306180-ffffffff8130619a: configfs_do_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *configfs_do_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81334190)
Location: fs/configfs/mount.c:105
Inline: False
```
**Symbols:**

```
ffffffff81334190-ffffffff813341aa: configfs_do_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *configfs_do_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8134b500)
Location: fs/configfs/mount.c:105
Inline: False
```
**Symbols:**

```
ffffffff8134b500-ffffffff8134b51a: configfs_do_mount (STB_LOCAL)
```
</details>
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
</ul>
