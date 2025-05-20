# Function: <code>kern_path_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c730)
Location: fs/namei.c:3475
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8121c730-ffffffff8121c765: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243bb0)
Location: fs/namei.c:3641
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81243bb0-ffffffff81243be5: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256b30)
Location: fs/namei.c:3598
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81256b30-ffffffff81256b65: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262cd0)
Location: fs/namei.c:3663
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81262cd0-ffffffff81262d05: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81285520)
Location: fs/namei.c:3661
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81285520-ffffffff81285555: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac660)
Location: fs/namei.c:3683
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ac660-ffffffff812ac695: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c1760)
Location: fs/namei.c:3673
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812c1760-ffffffff812c1795: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ddce0)
Location: fs/namei.c:3672
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ddce0-ffffffff812ddd19: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef800)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ef800-ffffffff812ef839: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813276c0)
Location: fs/namei.c:3496
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff813276c0-ffffffff813276f9: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332ad0)
Location: fs/namei.c:3498
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:handle_create
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff81332ad0-ffffffff81332b09: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338b30)
Location: fs/namei.c:3630
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81338b30-ffffffff81338b69: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386550)
Location: fs/namei.c:3692
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81386550-ffffffff8138659e: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814071a0)
Location: fs/namei.c:3786
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814071a0-ffffffff814071f8: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491560)
Location: fs/namei.c:3843
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81491560-ffffffff814915b8: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c5ba0)
Location: fs/namei.c:3923
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814c5ba0-ffffffff814c5bf8: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f8490)
Location: fs/namei.c:3932
Inline: False
Direct callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814f8490-ffffffff814f84e8: kern_path_create (STB_GLOBAL)
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
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398fb0)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010398fb0-ffff800010399004: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f64c)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c057f64c-c057f68c: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493680)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c000000000493680-c0000000004936d8: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266a9a)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe000266a9a-ffffffe000266ae6: kern_path_create (STB_GLOBAL)
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
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7de0)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e7de0-ffffffff812e7e19: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8a20)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d8a20-ffffffff812d8a59: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5bf0)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e5bf0-ffffffff812e5c29: kern_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *kern_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6b70)
Location: fs/namei.c:3667
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812f6b70-ffffffff812f6ba9: kern_path_create (STB_GLOBAL)
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
