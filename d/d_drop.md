# Function: <code>d_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812235c0)
Location: fs/dcache.c:491
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812235c0-ffffffff812235f2: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124bca0)
Location: fs/dcache.c:463
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff8124bca0-ffffffff8124bcd2: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ec80)
Location: fs/dcache.c:463
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff8125ec80-ffffffff8125ecb2: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c650)
Location: fs/dcache.c:497
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff8126c650-ffffffff8126c682: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e970)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff8128e970-ffffffff8128e9ab: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4a40)
Location: fs/dcache.c:491
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812b4a40-ffffffff812b4a7a: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9d00)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812c9d00-ffffffff812c9d3a: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e66f0)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812e66f0-ffffffff812e672c: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8250)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812f8250-ffffffff812f828c: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333b2f)
Location: fs/dcache.c:504
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff813310f0-ffffffff81331135: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f4af)
Location: fs/dcache.c:504
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff8133ca80-ffffffff8133cac5: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8134592f)
Location: fs/dcache.c:507
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff81342f00-ffffffff81342f45: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8139353f)
Location: fs/dcache.c:507
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff81390860-ffffffff813908a5: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414c7e)
Location: fs/dcache.c:532
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff81413080-ffffffff814130c9: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a019e)
Location: fs/dcache.c:532
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff8149e320-ffffffff8149e369: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d54be)
Location: fs/dcache.c:532
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff814d3640-ffffffff814d3689: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815078de)
Location: fs/dcache.c:533
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_for_umount
  - fs/dcache.c:shrink_dcache_for_umount
Direct callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:create_default_group
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/pstore/inode.c:pstore_put_backend_records
```
**Symbols:**

```
ffffffff81505dc0-ffffffff81505e09: d_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5af8)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffff8000103a5af8-ffff8000103a5b84: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588bb8)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
c0588bb8-c0588c08: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0b20)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
c0000000004a0b20-c0000000004a0bd8: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c7e4)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffe00026c7e4-ffffffe00026c85e: d_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0830)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812f0830-ffffffff812f086c: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1460)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812e1460-ffffffff812e149c: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee640)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff812ee640-ffffffff812ee67c: d_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_drop(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300280)
Location: fs/dcache.c:504
Inline: False
Direct callers:
  - fs/dcache.c:do_one_tree
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
**Symbols:**

```
ffffffff81300280-ffffffff813002ba: d_drop (STB_GLOBAL)
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
