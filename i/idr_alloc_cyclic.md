# Function: <code>idr_alloc_cyclic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eab80)
Location: lib/idr.c:488
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff813eab80-ffffffff813eabd8: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430f00)
Location: lib/idr.c:488
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81430f00-ffffffff81430f58: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144d110)
Location: lib/idr.c:488
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_setup_root
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff8144d110-ffffffff8144d168: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ec9e0)
Location: lib/idr.c:62
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff818ec9e0-ffffffff818eca3d: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819732e0)
Location: lib/idr.c:49
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff819732e0-ffffffff819733b1: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cee80)
Location: lib/idr.c:120
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff819cee80-ffffffff819cef35: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a08320)
Location: lib/idr.c:116
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81a08320-ffffffff81a083d5: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77c70)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81a77c70-ffffffff81a77d1b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf060)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81aaf060-ffffffff81aaf10b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8d90)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff815e8d90-ffffffff815e8e39: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160de40)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/io_uring.c:io_register_personality
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff8160de40-ffffffff8160dee9: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1590)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff815f1590-ffffffff815f163b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e700)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8165e700-ffffffff8165e7ab: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81777f20)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81777f20-ffffffff81777fdb: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020c40)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff82020c40-ffffffff82020cfb: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0c60)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff820a0c60-ffffffff820a0d1b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178c40)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff82178c40-ffffffff82178cfb: idr_alloc_cyclic (STB_GLOBAL)
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
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88880)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffff800010d88880-ffff800010d88958: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e8374c)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
c0e8374c-c0e83814: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9030)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
c000000000ec9030-c000000000ec9174: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2828)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffe0008b2828-ffffffe0008b28c8: idr_alloc_cyclic (STB_GLOBAL)
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
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4deb0)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81a4deb0-ffffffff81a4df5b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0afa0)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81a0afa0-ffffffff81a0b04b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba2a0)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81aba2a0-ffffffff81aba34b: idr_alloc_cyclic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int idr_alloc_cyclic(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac66f0)
Location: lib/idr.c:117
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
```
**Symbols:**

```
ffffffff81ac66f0-ffffffff81ac679b: idr_alloc_cyclic (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
