# Function: <code>free_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108c780)
Location: kernel/user.c:157
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:__prog_put_common
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:free_pipe_info
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_alloc
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - net/core/scm.c:__scm_destroy
```
**Symbols:**

```
ffffffff8108c780-ffffffff8108c820: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108f7f0)
Location: kernel/user.c:157
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/scm.c:__scm_destroy
```
**Symbols:**

```
ffffffff8108f7f0-ffffffff8108f890: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81094770)
Location: kernel/user.c:157
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/scm.c:__scm_destroy
```
**Symbols:**

```
ffffffff81094770-ffffffff81094810: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81091860)
Location: kernel/user.c:158
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/scm.c:__scm_destroy
```
**Symbols:**

```
ffffffff81091860-ffffffff81091904: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810986f0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/scm.c:__scm_destroy
```
**Symbols:**

```
ffffffff810986f0-ffffffff81098794: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8109be30)
Location: kernel/user.c:165
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8109be30-ffffffff8109bed7: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a4030)
Location: kernel/user.c:165
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810a4030-ffffffff810a40e0: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8d10)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810a8d10-ffffffff810a8db4: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810af2e0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810af2e0-ffffffff810af384: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b6ff0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:set_user
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810b6ff0-ffffffff810b7092: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b21b0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:set_user
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810b21b0-ffffffff810b2252: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b37f0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:set_user
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_ring_ctx_free
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810b37f0-ffffffff810b3892: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810c5990)
Location: kernel/user.c:178
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_ring_ctx_free
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/skbuff.c:msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810c5990-ffffffff810c5a3c: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810dcf80)
Location: kernel/user.c:178
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810dcf80-ffffffff810dd03a: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810fd180)
Location: kernel/user.c:178
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810fd180-ffffffff810fd23a: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81109180)
Location: kernel/user.c:178
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81109180-ffffffff8110923a: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81112b10)
Location: kernel/user.c:191
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/events/core.c:perf_mmap_close
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - io_uring/io_uring.c:io_ring_ctx_free
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81112b10-ffffffff81112bcf: free_uid (STB_GLOBAL)
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
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffff80001010a3a8)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffff80001010a3a8-ffff80001010a46c: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (c03633fc)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:set_user
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
```
**Symbols:**

```
c03633fc-c03634b8: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (c0000000001512f0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_unaccount_pages
```
**Symbols:**

```
c0000000001512f0-c0000000001513f4: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffe0000cce40)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe0000cce40-ffffffe0000ccebe: free_uid (STB_GLOBAL)
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
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a9650)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810a9650-ffffffff810a96f4: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81098010)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81098010-ffffffff810980b4: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8bb0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810a8bb0-ffffffff810a8c54: free_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_uid(struct user_struct *up);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b0cb0)
Location: kernel/user.c:164
Inline: False
Direct callers:
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/cred.c:put_cred_rcu
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_finish
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/events/core.c:perf_mmap_close
  - mm/mlock.c:user_shm_unlock
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_free
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - ipc/mqueue.c:mqueue_evict_inode
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/skbuff.c:mm_unaccount_pinned_pages
  - net/core/scm.c:__scm_destroy
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff810b0cb0-ffffffff810b0d54: free_uid (STB_GLOBAL)
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
