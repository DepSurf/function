# Function: <code>filp_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812097c0)
Location: fs/open.c:1078
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd
  - fs/file.c:do_close_on_exec
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812097c0-ffffffff81209830: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f5b0)
Location: fs/open.c:1089
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8122f5b0-ffffffff8122f621: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241b00)
Location: fs/open.c:1106
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81241b00-ffffffff81241b71: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124cea0)
Location: fs/open.c:1132
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8124cea0-ffffffff8124cf13: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126ee10)
Location: fs/open.c:1132
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:SYSC_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8126ee10-ffffffff8126ee86: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1174
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81297111-ffffffff81297125: filp_close.cold.22 (STB_LOCAL)
ffffffff81294ab0-ffffffff81294b17: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1141
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812abdc1-ffffffff812abdd5: filp_close.cold.19 (STB_LOCAL)
ffffffff812a9560-ffffffff812a95c7: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1161
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c85d1-ffffffff812c85e5: filp_close.cold (STB_LOCAL)
ffffffff812c5cd0-ffffffff812c5d3b: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d9fe1-ffffffff812d9ff5: filp_close.cold (STB_LOCAL)
ffffffff812d76e0-ffffffff812d774b: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1273
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff81310463-ffffffff81310477: filp_close.cold (STB_LOCAL)
ffffffff8130d890-ffffffff8130d8fb: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1271
Inline: False
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/io_uring.c:io_close
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff81bea480-ffffffff81bea494: filp_close.cold (STB_LOCAL)
ffffffff81319c90-ffffffff81319cfb: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1293
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff81bdc4ba-ffffffff81bdc4ce: filp_close.cold (STB_LOCAL)
ffffffff8131faa0-ffffffff8131fb0b: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1311
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/io_uring.c:io_close
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff81cc37b2-ffffffff81cc37c6: filp_close.cold (STB_LOCAL)
ffffffff8136d040-ffffffff8136d0ab: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1378
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - io_uring/io_uring.c:io_close
```
**Symbols:**

```
ffffffff81e75f03-ffffffff81e75f17: filp_close.cold (STB_LOCAL)
ffffffff813eb3a0-ffffffff813eb40f: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473670)
Location: fs/open.c:1410
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - io_uring/openclose.c:io_close
```
**Symbols:**

```
ffffffff81473670-ffffffff81473701: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a7e70)
Location: fs/open.c:1506
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - io_uring/openclose.c:io_close
```
**Symbols:**

```
ffffffff814a7e70-ffffffff814a7f04: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d8ab0)
Location: fs/open.c:1523
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - io_uring/openclose.c:io_close
```
**Symbols:**

```
ffffffff814d8ab0-ffffffff814d8adf: filp_close (STB_GLOBAL)
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
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037cac0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff80001037cac0-ffff80001037cb58: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c056741c)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c056741c-c05674a8: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000471db0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000471db0-c000000000471e84: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253044)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe000253044-ffffffe0002530c4: filp_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d25c1-ffffffff812d25d5: filp_close.cold (STB_LOCAL)
ffffffff812cfcc0-ffffffff812cfd2b: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c3241-ffffffff812c3255: filp_close.cold (STB_LOCAL)
ffffffff812c0940-ffffffff812c09ab: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d03d1-ffffffff812d03e5: filp_close.cold (STB_LOCAL)
ffffffff812cdad0-ffffffff812cdb3b: filp_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int filp_close(struct file *filp, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/open.c (0)
Location: fs/open.c:1166
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file.c:do_dup2
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e1201-ffffffff812e1215: filp_close.cold (STB_LOCAL)
ffffffff812de8e0-ffffffff812de94b: filp_close (STB_GLOBAL)
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
