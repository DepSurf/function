# Function: <code>get_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108cd8a)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810a20c9)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811730e9)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811815c9)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff811c3df6)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812155b7)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252010)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81253e87)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
```
In fs/eventpoll.c (ffffffff81255858)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_alloc
```
```
In ipc/mqueue.c (ffffffff8132c792)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff813344f1)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/scm.c (ffffffff8170ea10)
Location: include/linux/sched.h:2443
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:scm_fp_dup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108ff5a)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810a5879)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff81181aa1)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811933b8)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff811dfc26)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8123c417)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a7c0)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127c65f)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8127e098)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_alloc
```
```
In ipc/mqueue.c (ffffffff813613ee)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81369481)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/scm.c (ffffffff817766b7)
Location: include/linux/sched.h:2614
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
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
In kernel/signal.c (ffffffff81094eda)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810ab4d9)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff8118dcc8)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811a2b99)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff811efb76)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8124f115)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e370)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129020f)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
```
In fs/eventpoll.c (ffffffff81291c28)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_alloc
```
```
In ipc/mqueue.c (ffffffff81377be9)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff8137fc91)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/scm.c (ffffffff817a3937)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
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
In kernel/signal.c (ffffffff81091f6a)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810a8099)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff81192aaf)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811aa1ad)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff811faa96)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8125b065)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129d0af)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8129e988)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_alloc
```
```
In ipc/mqueue.c (ffffffff8138b766)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81393b11)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/scm.c (ffffffff817c1a97)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
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
In kernel/signal.c (ffffffff81098dfa)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810ae769)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811a0d6b)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811bdaa0)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81212fa6)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8127d417)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812c053f)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
```
In fs/eventpoll.c (ffffffff812c1df8)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_alloc
```
```
In ipc/mqueue.c (ffffffff813b0af6)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff813b91a1)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff818311c6)
Location: include/linux/sched/user.h:56
Inline: True
```
```
In net/core/scm.c (ffffffff8183b4a7)
Location: include/linux/sched/user.h:56
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
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
In kernel/signal.c (ffffffff8109c5ea)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810b5a94)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811b5d5d)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811ddcb6)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81233f36)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812a43a7)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e998d)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff812eb7c4)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In ipc/mqueue.c (ffffffff813e3185)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff813e9f31)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff8187b662)
Location: include/linux/sched/user.h:60
Inline: True
```
```
In net/core/scm.c (ffffffff81885ba7)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff819cd12d)
Location: include/linux/sched/user.h:60
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/signal.c (ffffffff810a484c)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810bec94)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811c5397)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811ee0b6)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812476e6)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812b9507)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fe504)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff812ff294)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In ipc/mqueue.c (ffffffff813fd965)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81404971)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff8189c4b2)
Location: include/linux/sched/user.h:61
Inline: True
```
```
In net/core/scm.c (ffffffff818a62d7)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81a06488)
Location: include/linux/sched/user.h:61
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a94cd)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810c4d03)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811d5123)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff81205b41)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812598f5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812d6157)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131f6a1)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff81320435)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff81332066)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff81429fb8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81431822)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff818e6d32)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff818f1767)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81a75db1)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afb01)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810cde13)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811e1833)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff81212ed7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81267dc5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812e7cc7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81332451)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff813331e5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff81345c26)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff81443ce8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff8144b582)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff81919112)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff819236b7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb14)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7958)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810d7b98)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff8120018a)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff8123ef50)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81297dd5)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8131fa97)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b125)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8136cfe8)
Location: include/linux/sched/user.h:57
Inline: True
```
```
In fs/io_uring.c (ffffffff8138579f)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In ipc/mqueue.c (ffffffff814949bc)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff8149d290)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff819ecd79)
Location: include/linux/sched/user.h:57
Inline: True
```
```
In net/core/scm.c (ffffffff819f7215)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81ba854d)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2bf7)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810d29c8)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811ff60a)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81249345)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812a2f25)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff8132afd7)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813789dc)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8137a748)
Location: include/linux/sched/user.h:57
Inline: True
```
```
In fs/io_uring.c (ffffffff813967d4)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In ipc/mqueue.c (ffffffff814b231c)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff814bad40)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff819eca39)
Location: include/linux/sched/user.h:57
Inline: True
```
```
In net/core/scm.c (ffffffff819f6c85)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82b1)
Location: include/linux/sched/user.h:57
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4239)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810d45e8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811fffbc)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8124d50f)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812a8785)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff81330fe7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff81381b75)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff81399e8e)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In ipc/mqueue.c (ffffffff814b818e)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff814c0c16)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff819d2f19)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff819dcdf4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7473)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e77c8)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff81231ce8)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8128711f)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In fs/pipe.c (ffffffff8137e767)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff813cedc5)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff813e8f5e)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In security/keys/process_keys.c (ffffffff8151964c)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff81a82bf9)
Location: include/linux/sched/user.h:48
Inline: True
```
```
In net/core/scm.c (ffffffff81a8d034)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81c7508d)
Location: include/linux/sched/user.h:48
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101a53)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff81274fa7)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff812db9f5)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In fs/pipe.c (ffffffff813fe807)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff81457994)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In security/keys/process_keys.c (ffffffff815ac21c)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In io_uring/io_uring.c (ffffffff81e925e7)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In net/core/skbuff.c (ffffffff81bf7928)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/scm.c (ffffffff81c02924)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81e19231)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126c23)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff812ca45c)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81343cb9)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In fs/pipe.c (ffffffff81488507)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff814e6c74)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In security/keys/process_keys.c (ffffffff816566ac)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In io_uring/io_uring.c (ffffffff8178cca0)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/rsrc.c (ffffffff817a1517)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In net/core/skbuff.c (ffffffff81da6679)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/scm.c (ffffffff81db1dc4)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0487)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811340c3)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff812f1b7c)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81374d42)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In fs/pipe.c (ffffffff814bd417)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff8151e784)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In security/keys/process_keys.c (ffffffff8168eeec)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In io_uring/io_uring.c (ffffffff817cddb6)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/rsrc.c (ffffffff817e2717)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In net/core/skbuff.c (ffffffff81e15785)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/scm.c (ffffffff81e2236a)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff8206c635)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113f064)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff813109ee)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8139e072)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In fs/pipe.c (ffffffff814ef8b7)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/eventpoll.c (ffffffff81552e25)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In security/keys/process_keys.c (ffffffff816cb43f)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In io_uring/io_uring.c (ffffffff81816999)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In net/core/skbuff.c (ffffffff81ed2b25)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/scm.c (ffffffff81ee02aa)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff82140433)
Location: include/linux/sched/user.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b4e8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffff80001012d070)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffff8000102648a8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffff80001029d26c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffff8000102fed74)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffff8000103909e8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ede88)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffff8000103f0520)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffff800010403c28)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffff800010529c5c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffff8000105351c4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffff800010bb2dc8)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffff800010bbdea8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffff800010d8137c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363da4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (c037d538)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (c0496a78)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (c04cca38)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (c051dda8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (c0577500)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (c05c56dc)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (c05c7854)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (c05d7b04)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (c06e2944)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (c06ec8b0)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (c0ccf944)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (c0cda350)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (c0e7b93c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000151f9c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (c00000000017634c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (c0000000003092b0)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (c00000000034dd24)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (c0000000003caa30)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (c000000000488844)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5754)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (c0000000004f9cb8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (c000000000510ad4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (c000000000674d3c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (c00000000068378c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (c000000000c89ca0)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (c000000000c976e0)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (c000000000ec12d4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd520)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffe0000e17f0)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffe0001a0526)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffe0001ce232)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffe00020cfcc)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffe000260262)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a267c)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffe0002a3ec8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffe0002b133e)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffe00038d5bc)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffe00039515a)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffe0007438a2)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffe00074c668)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad842)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9e71)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810c8193)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811d9e53)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff8120b527)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81260415)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812e02a7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8132aa31)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8132b7c5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff8133e206)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff8143c2c8)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81443b62)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff818b9112)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff818c36b7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81a4bea4)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098821)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810b69b3)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811ccc13)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff811fe2f7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff81252835)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812d0ee7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131b5d1)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8131d115)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff8132eec6)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff8142cd38)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff814345b2)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff81873062)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff8187d5f7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81a08a94)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a93d1)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810c76e3)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811d7c23)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff812092c7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff8125e1b5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812de0b7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81328501)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff81329295)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff8133bcd6)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff81438468)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff8143fd02)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff8190a112)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff819146b7)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d54)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b15fd)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/cred.c (ffffffff810cfbb3)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/bpf/syscall.c (ffffffff811e5fc3)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffff81218057)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff8126db95)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In fs/pipe.c (ffffffff812ef037)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8133a321)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8133b9b5)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/io_uring.c (ffffffff8134ee86)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
```
```
In ipc/mqueue.c (ffffffff8144c996)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/process_keys.c (ffffffff81456eb2)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/skbuff.c (ffffffff8192b212)
Location: include/linux/sched/user.h:54
Inline: True
```
```
In net/core/scm.c (ffffffff81935887)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4174)
Location: include/linux/sched/user.h:54
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
