# Function: <code>mount_pseudo_xattr</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *mount_pseudo_xattr(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct xattr_handler **xattr, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126f610)
Location: fs/libfs.c:239
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_mount
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - drivers/virtio/virtio_balloon.c:balloon_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff8126f610-ffffffff8126f7b0: mount_pseudo_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *mount_pseudo_xattr(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct xattr_handler **xattr, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127cdf0)
Location: fs/libfs.c:240
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_mount
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - drivers/virtio/virtio_balloon.c:balloon_mount
  - drivers/dax/super.c:dax_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff8127cdf0-ffffffff8127cf8d: mount_pseudo_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *mount_pseudo_xattr(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct xattr_handler **xattr, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129f890)
Location: fs/libfs.c:240
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_mount
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - drivers/virtio/virtio_balloon.c:balloon_mount
  - drivers/dax/super.c:dax_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff8129f890-ffffffff8129fa2d: mount_pseudo_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *mount_pseudo_xattr(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct xattr_handler **xattr, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c62b0)
Location: fs/libfs.c:240
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_mount
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - drivers/virtio/virtio_balloon.c:balloon_mount
  - drivers/dax/super.c:dax_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff812c62b0-ffffffff812c644e: mount_pseudo_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *mount_pseudo_xattr(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct xattr_handler **xattr, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812db4b0)
Location: fs/libfs.c:240
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_mount
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - drivers/virtio/virtio_balloon.c:balloon_mount
  - drivers/dax/super.c:dax_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff812db4b0-ffffffff812db64e: mount_pseudo_xattr (STB_GLOBAL)
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
</ul>
