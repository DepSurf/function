# Function: <code>mount_pseudo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *mount_pseudo(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81233a80)
Location: fs/libfs.c:211
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_mount
  - fs/nsfs.c:nsfs_mount
  - fs/block_dev.c:bd_mount
  - fs/anon_inodes.c:anon_inodefs_mount
  - fs/aio.c:aio_mount
  - net/socket.c:sockfs_mount
```
**Symbols:**

```
ffffffff81233a80-ffffffff81233c0c: mount_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *mount_pseudo(struct file_system_type *fs_type, char *name, const struct super_operations *ops, const struct dentry_operations *dops, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c0a0)
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
ffffffff8125c0a0-ffffffff8125c231: mount_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c826)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_mount
```
```
In fs/pipe.c (ffffffff8124e806)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - fs/pipe.c:pipefs_mount
```
```
In fs/nsfs.c (ffffffff8127d746)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - fs/nsfs.c:nsfs_mount
```
```
In fs/block_dev.c (ffffffff81282dc6)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - fs/block_dev.c:bd_mount
```
```
In fs/anon_inodes.c (ffffffff81293286)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - fs/anon_inodes.c:anon_inodefs_mount
```
```
In fs/aio.c (ffffffff81297c26)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - fs/aio.c:aio_mount
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81540236)
Location: include/linux/fs.h:2070
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81248456)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_mount
```
```
In fs/pipe.c (ffffffff8125a766)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - fs/pipe.c:pipefs_mount
```
```
In fs/nsfs.c (ffffffff8128b2b6)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - fs/nsfs.c:nsfs_mount
```
```
In fs/block_dev.c (ffffffff81290686)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - fs/block_dev.c:bd_mount
```
```
In fs/anon_inodes.c (ffffffff812a0526)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - fs/anon_inodes.c:anon_inodefs_mount
```
```
In fs/aio.c (ffffffff812a5b16)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - fs/aio.c:aio_mount
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815540b6)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon_mount
```
```
In drivers/dax/super.c (ffffffff8163d266)
Location: include/linux/fs.h:2120
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268616)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_mount
```
```
In fs/pipe.c (ffffffff8127cac6)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - fs/pipe.c:pipefs_mount
```
```
In fs/nsfs.c (ffffffff812ade06)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - fs/nsfs.c:nsfs_mount
```
```
In fs/block_dev.c (ffffffff812b3346)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - fs/block_dev.c:bd_mount
```
```
In fs/anon_inodes.c (ffffffff812c38f6)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - fs/anon_inodes.c:anon_inodefs_mount
```
```
In fs/aio.c (ffffffff812c9036)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - fs/aio.c:aio_mount
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7af6)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon_mount
```
```
In drivers/dax/super.c (ffffffff816a5fe6)
Location: include/linux/fs.h:2166
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128cf75)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_mount
```
```
In fs/pipe.c (ffffffff812a3a15)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - fs/pipe.c:pipefs_mount
```
```
In fs/nsfs.c (ffffffff812d5a65)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - fs/nsfs.c:nsfs_mount
```
```
In fs/block_dev.c (ffffffff812db045)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - fs/block_dev.c:bd_mount
```
```
In fs/anon_inodes.c (ffffffff812ecb75)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - fs/anon_inodes.c:anon_inodefs_mount
```
```
In fs/aio.c (ffffffff812f2065)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - fs/aio.c:aio_mount
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f0015)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon_mount
```
```
In drivers/dax/super.c (ffffffff816e1b35)
Location: include/linux/fs.h:2182
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a1ef5)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_mount
```
```
In fs/pipe.c (ffffffff812b8b65)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/pipe.c:pipefs_mount
```
```
In fs/nsfs.c (ffffffff812eae35)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/nsfs.c:nsfs_mount
```
```
In fs/block_dev.c (ffffffff812f0595)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/block_dev.c:bd_mount
```
```
In fs/anon_inodes.c (ffffffff81301585)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/anon_inodes.c:anon_inodefs_mount
```
```
In fs/aio.c (ffffffff81306a35)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - fs/aio.c:aio_mount
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a495)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon_mount
```
```
In drivers/dax/super.c (ffffffff81704f55)
Location: include/linux/fs.h:2268
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_mount
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
