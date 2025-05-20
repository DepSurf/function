# Function: <code>d_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224200)
Location: fs/dcache.c:2378
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:ns_get_path
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff81224200-ffffffff8122436b: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c8b0)
Location: fs/dcache.c:2311
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:ns_get_path
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff8124c8b0-ffffffff8124c957: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f8a0)
Location: fs/dcache.c:2320
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff8125f8a0-ffffffff8125f947: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126d1f0)
Location: fs/dcache.c:2350
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff8126d1f0-ffffffff8126d297: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128f590)
Location: fs/dcache.c:2362
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff8128f590-ffffffff8128f63f: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4e10)
Location: fs/dcache.c:2386
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff812b4e10-ffffffff812b4eb7: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca070)
Location: fs/dcache.c:2367
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
```
**Symbols:**

```
ffffffff812ca070-ffffffff812ca117: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6b10)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812e6b10-ffffffff812e6b8e: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8760)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812f8760-ffffffff812f87de: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813316b0)
Location: fs/dcache.c:2460
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813316b0-ffffffff8133173d: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d050)
Location: fs/dcache.c:2467
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8133d050-ffffffff8133d0dd: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813434d0)
Location: fs/dcache.c:2494
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813434d0-ffffffff8134355d: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390e20)
Location: fs/dcache.c:2495
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81390e20-ffffffff81390ead: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814130d0)
Location: fs/dcache.c:2520
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814130d0-ffffffff8141315d: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e380)
Location: fs/dcache.c:2554
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8149e380-ffffffff8149e40d: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d36a0)
Location: fs/dcache.c:2554
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814d36a0-ffffffff814d372d: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81505e20)
Location: fs/dcache.c:2378
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81505e20-ffffffff81505ead: d_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5ed8)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffff8000103a5ed8-ffff8000103a5ff0: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588c08)
Location: fs/dcache.c:2439
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/nsfs.c:__ns_get_path
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:detach_groups
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c0588c08-c0588ca0: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0be0)
Location: fs/dcache.c:2439
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c0000000004a0be0-c0000000004a0d00: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026cd72)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffe00026cd72-ffffffe00026ce54: d_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0d40)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812f0d40-ffffffff812f0dbe: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1970)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812e1970-ffffffff812e19ee: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eeb50)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812eeb50-ffffffff812eebce: d_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void d_delete(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813002c0)
Location: fs/dcache.c:2439
Inline: True
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813002c0-ffffffff8130033a: d_delete (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
