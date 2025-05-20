# Function: <code>idr_for_each</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int idr_for_each(struct idr *idp, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813e9bc0)
Location: lib/idr.c:686
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - lib/idr.c:idr_is_empty
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff813e9bc0-ffffffff813e9cc3: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int idr_for_each(struct idr *idp, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8142ffa0)
Location: lib/idr.c:686
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - lib/idr.c:idr_is_empty
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff8142ffa0-ffffffff814300a7: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int idr_for_each(struct idr *idp, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c1d0)
Location: lib/idr.c:686
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - lib/idr.c:idr_is_empty
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff8144c1d0-ffffffff8144c2d5: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ecab0)
Location: lib/idr.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff818ecab0-ffffffff818ecb87: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972ab0)
Location: lib/idr.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81972ab0-ffffffff81972b89: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf090)
Location: lib/idr.c:198
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff819cf090-ffffffff819cf18b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a08420)
Location: lib/idr.c:194
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a08420-ffffffff81a084e6: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77d60)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a77d60-ffffffff81a77e2b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf150)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81aaf150-ffffffff81aaf21b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8e80)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815e8e80-ffffffff815e8f4b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160df30)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8160df30-ffffffff8160dffb: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1680)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815f1680-ffffffff815f174b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e7f0)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8165e7f0-ffffffff8165e8bb: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778020)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81778020-ffffffff8177810a: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020d70)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff82020d70-ffffffff82020e5a: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0d90)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff820a0d90-ffffffff820a0e7a: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178d70)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/gpu/drm/drm_gem.c:drm_gem_release
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_release
  - drivers/gpu/drm/drm_debugfs.c:drm_gem_name_info
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet_has_id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff82178d70-ffffffff82178e5a: idr_for_each (STB_GLOBAL)
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
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88998)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffff800010d88998-ffff800010d88a84: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83850)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
c0e83850-c0e83964: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9200)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
c000000000ec9200-c000000000ec9364: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2906)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffe0008b2906-ffffffe0008b299e: idr_for_each (STB_GLOBAL)
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
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4dfa0)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a4dfa0-ffffffff81a4e06b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b090)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a0b090-ffffffff81a0b15b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba390)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81aba390-ffffffff81aba45b: idr_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int idr_for_each(const struct idr *idr, int (*fn)(int, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac67e0)
Location: lib/idr.c:195
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/shm.c:shm_destroy_orphaned
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_unregister_transfer
  - drivers/scsi/sg.c:dev_seq_start
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81ac67e0-ffffffff81ac68ab: idr_for_each (STB_GLOBAL)
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
<code>const struct idr *idr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr *idp</code>
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
