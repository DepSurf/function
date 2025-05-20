# Function: <code>hash_32</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063872)
Location: include/linux/hash.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/workqueue.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In lib/iommu-common.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In net/ipv4/route.c (ffffffff8175471c)
Location: include/linux/hash.h:62
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81780fde)
Location: include/linux/hash.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81791290)
Location: include/linux/hash.h:62
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/hash.h:62
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817c938c)
Location: include/linux/hash.h:62
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109f175)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff810f3d27)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff811a51f4)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In mm/kfence/core.c (ffffffff813afa6f)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/dcache.c (ffffffff81413165)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81454196)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/mbcache.c (ffffffff81481cdc)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8156189a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8156279a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff815d6038)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff81635ec0)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
```
```
In security/safesetid/securityfs.c (ffffffff81636138)
Location: include/linux/hash.h:65
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dca5b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff819e907a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81c0c1ee)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81c984fe)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81ca00be)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d118ab)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81d27dde)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81d33ee0)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b67d)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv6/anycast.c (ffffffff81d86d33)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d9a8cf)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In arch/x86/kernel/kvm.c (ffffffff810b66d5)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff81115f77)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff811e4b54)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In mm/kfence/core.c (ffffffff81430039)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/dcache.c (ffffffff8149e425)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e3046)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/mbcache.c (ffffffff81514f4b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81603fba)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8160518a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff8168425b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff816eca76)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
```
```
In security/safesetid/securityfs.c (ffffffff816ed128)
Location: include/linux/hash.h:65
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b580eb)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81b656aa)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81dc49fe)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81e5449e)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81e5c05e)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed766b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81eef79e)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81efc370)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0404d)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv6/anycast.c (ffffffff81f548f3)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f6971f)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In arch/x86/kernel/kvm.c (ffffffff810b97e5)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff81122d17)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff811549e6)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/time/posix-timers.c (ffffffff811f91b4)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/trace/trace_events_user.c (ffffffff812c680c)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:find_user_event
```
```
In mm/memory.c (ffffffff813f0fa4)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/kfence/core.c (ffffffff814659c9)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/dcache.c (ffffffff814d3745)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519939)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/mbcache.c (ffffffff8154c94b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8163beda)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8163d09a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff816bc5cb)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff81726ea6)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
```
```
In security/safesetid/securityfs.c (ffffffff81727548)
Location: include/linux/hash.h:65
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bab65b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81bb8cca)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81e38efe)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:netdev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81eafd3e)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81eb8bee)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36a5b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81f3d416)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/devinet.c (ffffffff81f4f15e)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81f5bd90)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63a2d)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv6/anycast.c (ffffffff81fb4303)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc978f)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/raw.c (ffffffff81fef0a2)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In arch/x86/kernel/kvm.c (ffffffff810c0c05)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff8112cd5b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff811698f2)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/time/posix-timers.c (ffffffff8120f3a4)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/trace/trace_events_user.c (ffffffff812e32c2)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:find_user_event
```
```
In mm/memory.c (ffffffff8141bcc3)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/kfence/core.c (ffffffff81494ca9)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/dcache.c (ffffffff81505ec5)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154dd19)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/mbcache.c (ffffffff8158277b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8167543a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8167660a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff816f90fb)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff817680f6)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgid
  - security/safesetid/lsm.c:safesetid_task_fix_setuid
  - security/safesetid/lsm.c:safesetid_security_capable
  - security/safesetid/lsm.c:safesetid_security_capable
```
```
In security/safesetid/securityfs.c (ffffffff817687e8)
Location: include/linux/hash.h:65
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff99b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81c0d32a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81ef719a)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:netdev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81f727ae)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81f7bcbe)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcb7b)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff82003576)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/devinet.c (ffffffff820152be)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff820222f0)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff82029ffd)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv6/anycast.c (ffffffff82081bb3)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff82096f2f)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/raw.c (ffffffff820bcc71)
Location: include/linux/hash.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
