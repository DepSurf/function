# Function: <code>getname_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121bcc0)
Location: fs/namei.c:210
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:kern_path_create
  - fs/namei.c:kern_path_locked
  - fs/namei.c:do_file_open_root
```
**Symbols:**

```
ffffffff8121bcc0-ffffffff8121bdd2: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243150)
Location: fs/namei.c:212
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81243150-ffffffff81243260: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812560d0)
Location: fs/namei.c:212
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812560d0-ffffffff812561e0: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262270)
Location: fs/namei.c:212
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81262270-ffffffff81262380: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284ab0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81284ab0-ffffffff81284bc0: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812abc20)
Location: fs/namei.c:215
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812abc20-ffffffff812abd30: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c0d20)
Location: fs/namei.c:215
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c0d20-ffffffff812c0e30: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dd4e0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812dd4e0-ffffffff812dd5fb: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef010)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812ef010-ffffffff812ef12b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81326fc0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81326fc0-ffffffff813270db: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813323d0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813323d0-ffffffff813324eb: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81338420)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81338420-ffffffff8133853b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386110)
Location: fs/namei.c:221
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81386110-ffffffff8138622b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406d10)
Location: fs/namei.c:222
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81406d10-ffffffff81406e2d: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491070)
Location: fs/namei.c:222
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81491070-ffffffff8149118d: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bf3b0)
Location: fs/namei.c:223
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814bf3b0-ffffffff814bf538: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f17b0)
Location: fs/namei.c:223
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
  - fs/exec.c:kernel_execve
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/init.c:init_rmdir
  - fs/init.c:init_unlink
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814f17b0-ffffffff814f1967: getname_kernel (STB_GLOBAL)
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
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398798)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff800010398798-ffff8000103988bc: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057ee80)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c057ee80-c057ef94: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000492ae0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000492ae0-c000000000492cfc: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266442)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe000266442-ffffffe00026652c: getname_kernel (STB_GLOBAL)
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
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e75f0)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e75f0-ffffffff812e770b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8230)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d8230-ffffffff812d834b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5400)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e5400-ffffffff812e551b: getname_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct filename *getname_kernel(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6380)
Location: fs/namei.c:213
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/open.c:filp_open
  - fs/exec.c:open_exec
  - fs/namei.c:kern_path_create
  - fs/namei.c:do_file_open_root
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/namei.c:kern_path_locked
  - fs/fs_parser.c:fs_lookup_param
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812f6380-ffffffff812f649b: getname_kernel (STB_GLOBAL)
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
