# Function: <code>current_umask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81241300)
Location: fs/fs_struct.c:154
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - ipc/mqueue.c:do_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81241300-ffffffff8124131e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81269630)
Location: fs/fs_struct.c:154
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81269630-ffffffff8126964e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8127c5e0)
Location: fs/fs_struct.c:154
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8127c5e0-ffffffff8127c5fe: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81289cb0)
Location: fs/fs_struct.c:155
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81289cb0-ffffffff81289cce: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812ac7f0)
Location: fs/fs_struct.c:155
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ac7f0-ffffffff812ac80e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812d43d0)
Location: fs/fs_struct.c:155
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d43d0-ffffffff812d43ee: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812e97a0)
Location: fs/fs_struct.c:155
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:path_openat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e97a0-ffffffff812e97be: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81308160)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81308160-ffffffff8130817e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8131b200)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8131b200-ffffffff8131b21e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81354eb0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81354eb0-ffffffff81354ece: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813617d0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813617d0-ffffffff813617ee: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813682b0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813682b0-ffffffff813682ce: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813b6fb0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff813b6fb0-ffffffff813b6fce: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8143c5d0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:vfs_tmpfile
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/posix_acl.c:posix_acl_create
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8143c5d0-ffffffff8143c5f2: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff814cacc0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:do_mknodat
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/posix_acl.c:posix_acl_create
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814cacc0-ffffffff814cace2: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81500f00)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:do_mknodat
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/posix_acl.c:posix_acl_create
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81500f00-ffffffff81500f22: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81535b20)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:do_mknodat
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/init.c:init_mkdir
  - fs/init.c:init_mknod
  - fs/posix_acl.c:posix_acl_create
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81535b20-ffffffff81535b42: current_umask (STB_GLOBAL)
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
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffff8000103d2580)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff8000103d2580-ffff8000103d25a4: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c05ad238)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:__se_sys_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c05ad238-c05ad268: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c0000000004d5090)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c0000000004d5090-c0000000004d50a8: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffe00028d8e2)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:__se_sys_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe00028d8e2-ffffffe00028d902: current_umask (STB_GLOBAL)
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
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813137e0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813137e0-ffffffff813137fe: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813043f0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813043f0-ffffffff8130440e: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813115d0)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813115d0-ffffffff813115ee: current_umask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int current_umask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81322e20)
Location: fs/fs_struct.c:156
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mkdirat
  - fs/namei.c:lookup_open
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81322e20-ffffffff81322e3e: current_umask (STB_GLOBAL)
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
