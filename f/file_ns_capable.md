# Function: <code>file_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a290)
Location: kernel/capability.c:420
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
**Symbols:**

```
ffffffff8108a290-ffffffff8108a2e5: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d1c0)
Location: kernel/capability.c:446
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff8108d1c0-ffffffff8108d211: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092170)
Location: kernel/capability.c:447
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff81092170-ffffffff810921c1: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f320)
Location: kernel/capability.c:447
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff8108f320-ffffffff8108f346: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810961e0)
Location: kernel/capability.c:448
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810961e0-ffffffff81096207: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810996e0)
Location: kernel/capability.c:448
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810996e0-ffffffff81099707: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1a70)
Location: kernel/capability.c:449
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810a1a70-ffffffff810a1a99: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a64a0)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_open
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810a64a0-ffffffff810a64c8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810aca80)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810aca80-ffffffff810acaa8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b47a0)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810b47a0-ffffffff810b47c8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810af990)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810af990-ffffffff810af9b8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b0f50)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810b0f50-ffffffff810b0f78: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c2760)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810c2760-ffffffff810c2788: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810d9bf0)
Location: kernel/capability.c:467
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810d9bf0-ffffffff810d9c30: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810f9b80)
Location: kernel/capability.c:467
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff810f9b80-ffffffff810f9bc0: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81105e90)
Location: kernel/capability.c:453
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff81105e90-ffffffff81105ecd: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110f7e0)
Location: kernel/capability.c:453
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_gid_file_write
  - security/safesetid/securityfs.c:safesetid_uid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
```
**Symbols:**

```
ffffffff8110f7e0-ffffffff8110f81d: file_ns_capable (STB_GLOBAL)
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
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010105978)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffff800010105978-ffff8000101059e8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360dc8)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
c0360dc8-c0360e3c: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d0f0)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
c00000000014d0f0-c00000000014d14c: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000caf8c)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffe0000caf8c-ffffffe0000cafe8: file_ns_capable (STB_GLOBAL)
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
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6df0)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810a6df0-ffffffff810a6e18: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810957d0)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810957d0-ffffffff810957f8: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6350)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810a6350-ffffffff810a6378: file_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool file_ns_capable(const struct file *file, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae430)
Location: kernel/capability.c:466
Inline: False
Direct callers:
  - kernel/resource.c:r_show
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:map_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_stack
  - security/safesetid/securityfs.c:safesetid_file_write
  - drivers/pci/pci-sysfs.c:pci_read_config
  - net/core/sock.c:sk_ns_capable
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:__netlink_ns_capable
```
**Symbols:**

```
ffffffff810ae430-ffffffff810ae458: file_ns_capable (STB_GLOBAL)
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
