# Function: <code>put_ipc_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8132eb50)
Location: ipc/namespace.c:121
Inline: True
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_create
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8132eb50-ffffffff8132ebdf: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81363810)
Location: ipc/namespace.c:120
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_create
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff81363810-ffffffff81363896: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8137a020)
Location: ipc/namespace.c:143
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_create
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8137a020-ffffffff8137a0b7: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8138dbf0)
Location: ipc/namespace.c:145
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_create
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8138dbf0-ffffffff8138dc89: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813b3070)
Location: ipc/namespace.c:158
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_create
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff813b3070-ffffffff813b3109: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813e37b0)
Location: ipc/namespace.c:158
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff813e37b0-ffffffff813e3849: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff813fdd10)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff813fdd10-ffffffff813fdda9: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8142a340)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8142a340-ffffffff8142a3e0: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff81444070)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff81444070-ffffffff81444110: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/namespace.c (ffffffff814952b5)
Location: ipc/namespace.c:165
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff81494fd0-ffffffff8149502e: put_ipc_ns.part.0 (STB_LOCAL)
ffffffff81495030-ffffffff81495062: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/namespace.c (ffffffff814b2d15)
Location: ipc/namespace.c:165
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff814b29f0-ffffffff814b2a4e: put_ipc_ns.part.0 (STB_LOCAL)
ffffffff814b2a50-ffffffff814b2a89: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/namespace.c (ffffffff814b89a5)
Location: ipc/namespace.c:165
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff814b8870-ffffffff814b88ce: put_ipc_ns.part.0 (STB_LOCAL)
ffffffff814b88d0-ffffffff814b8909: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/namespace.c (ffffffff815111d5)
Location: ipc/namespace.c:165
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/shm.c:exit_shm
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff815110a0-ffffffff815110fe: put_ipc_ns.part.0 (STB_LOCAL)
ffffffff81511100-ffffffff81511139: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff815a32a0)
Location: ipc/namespace.c:178
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/shm.c:exit_shm
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff815a32a0-ffffffff815a332e: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8164ce70)
Location: ipc/namespace.c:181
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/shm.c:exit_shm
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8164ce70-ffffffff8164cefe: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff816853b0)
Location: ipc/namespace.c:198
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/shm.c:exit_shm
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff816853b0-ffffffff8168543e: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff816c17d0)
Location: ipc/namespace.c:198
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/shm.c:exit_shm
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff816c17d0-ffffffff816c185e: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffff80001052cab8)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffff80001052cab8-ffff80001052cb8c: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (c06e53c0)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
c06e53c0-c06e5490: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (c0000000006789d0)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
c0000000006789d0-c000000000678b30: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffe00038e9cc)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffe00038e9cc-ffffffe00038eac6: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8143c650)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8143c650-ffffffff8143c6f0: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8142d0c0)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8142d0c0-ffffffff8142d160: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff814387f0)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff814387f0-ffffffff81438890: put_ipc_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_ipc_ns(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/namespace.c (ffffffff8144f950)
Location: ipc/namespace.c:146
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - ipc/util.c:sysvipc_proc_release
  - ipc/shm.c:shm_release
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_fs_context_free
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8144f950-ffffffff8144f9ee: put_ipc_ns (STB_GLOBAL)
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
