# Function: <code>done_path_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216880)
Location: fs/namei.c:3483
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81216880-ffffffff812168c5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d8c0)
Location: fs/namei.c:3649
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8123d8c0-ffffffff8123d905: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250660)
Location: fs/namei.c:3606
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81250660-ffffffff812506a5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125c7f0)
Location: fs/namei.c:3671
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8125c7f0-ffffffff8125c835: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127eb10)
Location: fs/namei.c:3669
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8127eb10-ffffffff8127eb55: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a54a0)
Location: fs/namei.c:3691
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812a54a0-ffffffff812a54e5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ba610)
Location: fs/namei.c:3681
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ba610-ffffffff812ba655: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7210)
Location: fs/namei.c:3680
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d7210-ffffffff812d7255: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8d70)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e8d70-ffffffff812e8db5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81329591)
Location: fs/namei.c:3504
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff81322010-ffffffff81322058: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333811)
Location: fs/namei.c:3506
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff8132d5c0-ffffffff8132d608: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813398d6)
Location: fs/namei.c:3638
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81332f60-ffffffff81332fa8: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8138801d)
Location: fs/namei.c:3703
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff813806f0-ffffffff81380738: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81408f70)
Location: fs/namei.c:3797
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81400a00-ffffffff81400a52: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814935ba)
Location: fs/namei.c:3854
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8148a920-ffffffff8148a972: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8610)
Location: fs/namei.c:3934
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814c1030-ffffffff814c1082: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814faeb0)
Location: fs/namei.c:3943
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814f34f0-ffffffff814f3542: done_path_create (STB_GLOBAL)
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
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392168)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010392168-ffff8000103921c0: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05796cc)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c05796cc-c0579718: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048a930)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c00000000048a930-c00000000048a9ac: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261346)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe000261346-ffffffe0002613a4: done_path_create (STB_GLOBAL)
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
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1350)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e1350-ffffffff812e1395: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d1f90)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d1f90-ffffffff812d1fd5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df160)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812df160-ffffffff812df1a5: done_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void done_path_create(struct path *path, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0550)
Location: fs/namei.c:3675
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812f0550-ffffffff812f0595: done_path_create (STB_GLOBAL)
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
