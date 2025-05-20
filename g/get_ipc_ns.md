# Function: <code>get_ipc_ns</code>

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
In ipc/util.c (ffffffff8132471b)
Location: include/linux/ipc_namespace.h:119
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8132b5bb)
Location: include/linux/ipc_namespace.h:119
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8132c8ab)
Location: include/linux/ipc_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In ipc/namespace.c (ffffffff8132e96f)
Location: include/linux/ipc_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:ipcns_install
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
In ipc/util.c (ffffffff8135930b)
Location: include/linux/ipc_namespace.h:117
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81360222)
Location: include/linux/ipc_namespace.h:117
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8136150b)
Location: include/linux/ipc_namespace.h:117
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In ipc/namespace.c (ffffffff81363906)
Location: include/linux/ipc_namespace.h:117
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8136f7fb)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81376a39)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff81377d0b)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In ipc/namespace.c (ffffffff8137a126)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff81382d2b)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8138a601)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8138b897)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In ipc/namespace.c (ffffffff8138dcf6)
Location: include/linux/ipc_namespace.h:118
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff813a6ccb)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff813af771)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff813b0c27)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create
```
```
In ipc/namespace.c (ffffffff813b3176)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff813d5f0b)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff813df544)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff813e3226)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In ipc/namespace.c (ffffffff813e38b6)
Location: include/linux/ipc_namespace.h:126
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff813f05cb)
Location: include/linux/ipc_namespace.h:128
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff813f9c92)
Location: include/linux/ipc_namespace.h:128
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff813fda16)
Location: include/linux/ipc_namespace.h:128
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
```
```
In ipc/namespace.c (ffffffff813fde56)
Location: include/linux/ipc_namespace.h:128
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8141c8eb)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81426298)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8142a05a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142a486)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8143673b)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8143ffe8)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff81443d8a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814441b6)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff814867af)
Location: include/linux/ipc_namespace.h:131
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81490d68)
Location: include/linux/ipc_namespace.h:131
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff81494ce7)
Location: include/linux/ipc_namespace.h:131
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814952c8)
Location: include/linux/ipc_namespace.h:131
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff814a3e52)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff814ae4ba)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff814b2647)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b2d2d)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff814a9d82)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff814b42e7)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff814b84b7)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b89bd)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff81502232)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8150c981)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff81510ce7)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815111ed)
Location: include/linux/ipc_namespace.h:130
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8159389f)
Location: include/linux/ipc_namespace.h:137
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8159e91b)
Location: include/linux/ipc_namespace.h:137
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff815a2eec)
Location: include/linux/ipc_namespace.h:137
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815a3556)
Location: include/linux/ipc_namespace.h:137
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8163c41f)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81647fdb)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8164ca4c)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8164d166)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8167489f)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff816804ff)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff816851ac)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81685906)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff816b0c5f)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff816bc91e)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff816c15cc)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1d26)
Location: include/linux/ipc_namespace.h:138
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffff80001051cc10)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffff8000105287a4)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffff80001052c498)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cc24)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (c06d9018)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (c06e1c90)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (c06e2c00)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5528)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (c000000000665a08)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (c000000000673284)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (c000000000674e8c)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c000000000678bd4)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffe0003845cc)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffe00038be22)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffe00038d688)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffe00038eb4a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8142ed1b)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff814385c8)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8143c36a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8143c796)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8141f79b)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81429038)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8142cdda)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142d206)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff8142aebb)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff81434768)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8143850a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81438936)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
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
In ipc/util.c (ffffffff81441d7b)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/shm.c (ffffffff8144b88d)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff8144f54a)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8144fa96)
Location: include/linux/ipc_namespace.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
</details>
</li>
</ul>

## Differences
