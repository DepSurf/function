# Function: <code>hlist_del_init_rcu</code>

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
In mm/mmu_notifier.c (ffffffff811e3d2e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff8122bf08)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/inode_mark.c (ffffffff8124fecb)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8125061e)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff81250c97)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In block/blk-cgroup.c (ffffffff813d84b6)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/devinet.c (ffffffff8178f7aa)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff817cdf47)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In mm/mmu_notifier.c (ffffffff812027ce)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff81254678)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/inode_mark.c (ffffffff8127862b)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff81278c92)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff81279497)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In block/blk-cgroup.c (ffffffff8141e1f8)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/ipv4/udp.c (ffffffff817f3f54)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff817fcd4a)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff8183b3e3)
Location: include/linux/rculist.h:155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In mm/mmu_notifier.c (ffffffff8121460e)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812698ab)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/inode_mark.c (ffffffff8128c30f)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8128c8c2)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff8128d05b)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In block/blk-cgroup.c (ffffffff814397b8)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/sched/sch_api.c (ffffffff817df677)
Location: include/linux/rculist.h:153
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81825164)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff8182dcaa)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff8186cdc1)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In mm/mmu_notifier.c (ffffffff8121fa8e)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff8127704b)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff81299649)
Location: include/linux/rculist.h:153
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812d43e1)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81446fb9)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/sched/sch_api.c (ffffffff817febc8)
Location: include/linux/rculist.h:153
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81845eef)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff8184f17a)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff818916f8)
Location: include/linux/rculist.h:153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff8110316b)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
```
In mm/mmu_notifier.c (ffffffff8123ac9c)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff81299a87)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff812bc9b1)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8c0d)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81473b90)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/sched/sch_api.c (ffffffff8187c854)
Location: include/linux/rculist.h:154
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c5917)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff818ceda6)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff81913321)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff8110b6b5)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In mm/mmu_notifier.c (ffffffff8125e05d)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812bf927)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff812e5559)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff81326506)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff814a800d)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/sched/sch_api.c (ffffffff818cf073)
Location: include/linux/rculist.h:154
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2344)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff8191d990)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819251e6)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/addrconf.c (ffffffff8196ab09)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81116ea5)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In mm/mmu_notifier.c (ffffffff812728dc)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812d4b27)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff812fa1a6)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d3be)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff814c1cb7)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/sched/sch_api.c (ffffffff818fa713)
Location: include/linux/rculist.h:154
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fd44)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff8194c240)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81953ff6)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81993e59)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff8199fad9)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81121125)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In mm/mmu_notifier.c (ffffffff8128de9d)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812f2000)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff8131aba0)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff813656d5)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff814f0369)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81952c79)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff81959fc5)
Location: include/linux/rculist.h:154
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982654)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff819b0c70)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819b8a56)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff819ff8e9)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a0bdbf)
Location: include/linux/rculist.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff8112d745)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff811ff335)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffff8129dd93)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff81303bc0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff8132d710)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d965)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81509816)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81988fc9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff81990465)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819953e0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8ed0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff819e7bc3)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819ef756)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81a364c9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a42a6f)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff8113bec5)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff81227245)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff8124d43a)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812d2083)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In fs/inode.c (ffffffff81335b4a)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81340995)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff813677b0)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff813b9e7f)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813be94e)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8c0e)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81569c2c)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60c69)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff81a67f78)
Location: include/linux/rculist.h:182
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a6e230)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3997)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff81ad4b47)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81add6b6)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81b2c019)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b3948e)
Location: include/linux/rculist.h:182
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff811365d5)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff8122dd95)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fbf9)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/watch_queue.c (ffffffff8125789a)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812ddaa3)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In fs/inode.c (ffffffff813414ca)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8134ca25)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff81374b10)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff813cb90f)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d071e)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813dabfe)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff8158453c)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/dev.c (ffffffff81a061d9)
Location: include/linux/rculist.h:190
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a70688)
Location: include/linux/rculist.h:190
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a76c00)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadfd7)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff81ae1087)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81aea3e6)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81b3aa39)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b4818e)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff811373c5)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812251ac)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/devmap.c (ffffffff81232ee5)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff8125bcfa)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812e5143)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff81347a7a)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff813535f3)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff8137b4d0)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff813d28ff)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d761e)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813e181e)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff8158b33c)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/dev.c (ffffffff819ecd09)
Location: include/linux/rculist.h:190
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a58f88)
Location: include/linux/rculist.h:190
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a5e9d0)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a990b7)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff81accfe7)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81ad5b36)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81b28719)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b35d8e)
Location: include/linux/rculist.h:190
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff8115a075)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d140)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/devmap.c (ffffffff8126c345)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81297baa)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8132d323)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff8139567a)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff813a1a43)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff813c8210)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff81423e4f)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81428d5e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff8143332e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff815f0365)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/dev.c (ffffffff81a9de91)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b122c9)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81b17ba0)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54534)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff81b8b967)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81b94b68)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81bee6d9)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81bfc4ee)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81183504)
Location: include/linux/rculist.h:181
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7280)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/devmap.c (ffffffff812bb089)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff812ede76)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8139cf93)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff8141760c)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff81425450)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff8144f36e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff8149c9a4)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814a2058)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff814ad24e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff816a15b5)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3eec9)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In net/core/dev.c (ffffffff81c0f00f)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c995d5)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81c9fa1e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/udp.c (ffffffff81d18d06)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81d26618)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81d86c3a)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81d95e26)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/printk/printk.c (ffffffff8118da2a)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/livepatch/shadow.c (ffffffff811be684)
Location: include/linux/rculist.h:181
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305950)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/devmap.c (ffffffff8131e4b9)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81358296)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8141c3d3)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff814a2d7c)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814b1bd0)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff814ddbde)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff815313a4)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81537148)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff815436be)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81760425)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd5279)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In net/core/dev.c (ffffffff81dbed4f)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e558d5)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81e5bcce)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/udp.c (ffffffff81edf411)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff81eeded8)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81f547ea)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81f646d6)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/printk/printk.c (ffffffff8119f1da)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/livepatch/shadow.c (ffffffff811d10b4)
Location: include/linux/rculist.h:181
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81333ec2)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/devmap.c (ffffffff8134e2ab)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81389ac2)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8144f983)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff814d7ecc)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814e6c1f)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff815143c3)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff81569553)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156f338)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff8157bb1e)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff8179f799)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cf09)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In net/core/dev.c (ffffffff81e2e91f)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb1175)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81eb84cc)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/udp.c (ffffffff81f3e8d5)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff81f4d898)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81fb41fa)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81fc47c6)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/printk/printk.c (ffffffff811ae3b0)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/livepatch/shadow.c (ffffffff811e5d34)
Location: include/linux/rculist.h:181
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813585b2)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/devmap.c (ffffffff813757ab)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/watch_queue.c (ffffffff813b3512)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff81489663)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/inode.c (ffffffff8150a6ac)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8151aa5f)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/notify/mark.c (ffffffff81548893)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/inode.c (ffffffff815a1b73)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a7cf7)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff815b43ce)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff817e3269)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3869)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In net/core/dev.c (ffffffff81eed29f)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f73c15)
Location: include/linux/rculist.h:181
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81f7b59c)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/udp.c (ffffffff82004c25)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff820139a8)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff82081aaa)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff82091d76)
Location: include/linux/rculist.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In virt/kvm/eventfd.c (ffff8000100c0f80)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_unregister_irq_ack_notifier
```
```
In kernel/bpf/devmap.c (ffff800010287010)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffff80001033cf2c)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffff8000103b7224)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffff8000103e9b90)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa14)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffff80001060c5f0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffff800010c31324)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffff800010c3c3c0)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c41fe4)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a7d0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffff800010c9bb3c)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffff800010ca55c8)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffff800010cf7018)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffff800010d0501c)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/bpf/devmap.c (c04b6920)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (c0543680)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (c05958cc)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (c05c0c7c)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (c060f8bc)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (c07b7d64)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (c0d480c4)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (c0d4e304)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (c0d53d78)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (c0d798b0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (c0da79cc)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (c0db1f04)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (c0dfd504)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (c0e0c1a0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (c0000000001f2360)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (c000000000331790)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (c000000000418384)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (c0000000004b3ccc)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (c0000000004f02f4)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (c000000000561188)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (c0000000007a9440)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (c000000000d2a2d4)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (c000000000d36038)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (c000000000d3df98)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f948)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (c000000000dab718)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (c000000000db9454)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (c000000000e1d874)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (c000000000e2ef50)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/bpf/devmap.c (ffffffe0001bb652)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffe0002328b0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffe000279e12)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffe00029e542)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffe0002dfd64)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffe000445098)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a70aa)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffe0007accf0)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffe0007b1824)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d02c4)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffe0007f9db2)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffe000800eca)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffe000842506)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffe00084f5ca)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81125d25)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff811f7955)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffff81296373)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812fc1a0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff81325cf0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff81375f45)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81501df6)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81928e39)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff819302d5)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81935250)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958d40)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff81987a33)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff8198f4f6)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff819d5b59)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff819e20ff)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81118785)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff811ea6a5)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffff81287f83)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812ecdc0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff81316890)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff81366a15)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff814f2306)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/net/vxlan.c (ffffffff81770994)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_sock_release
  - drivers/net/vxlan.c:vxlan_sock_release
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2be9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff818e9dd5)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818eed50)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912830)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff819414f3)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81948fb6)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/ip_tunnel.c (ffffffff819669da)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_uninit
  - net/ipv4/ip_tunnel.c:ip_tunnel_dellink
  - net/ipv4/ip_tunnel.c:ip_tunnel_update
```
```
In net/ipv6/anycast.c (ffffffff81992919)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff8199eebf)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81123c15)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff811f5725)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffff81294183)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff812f9f90)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff813237c0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff81373a15)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff814fde86)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff81979fc9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff81981465)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819863e0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3510)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff819f2203)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819f9d96)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81a405d9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a4cb7f)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
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
In kernel/livepatch/shadow.c (ffffffff81130255)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/bpf/devmap.c (ffffffff81203c85)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In mm/mmu_notifier.c (ffffffff812a3fb3)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/namespace.c (ffffffff8130b2e0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/notify/mark.c (ffffffff8133546d)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/proc/proc_sysctl.c (ffffffff81386fa5)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In block/blk-cgroup.c (ffffffff81517666)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c4f9)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff819a39e5)
Location: include/linux/rculist.h:172
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819a93e0)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd1e3)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/udp.c (ffffffff819f95f3)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81a040a6)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv6/anycast.c (ffffffff81a4bf99)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a58aef)
Location: include/linux/rculist.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
</details>
</li>
</ul>

## Differences
