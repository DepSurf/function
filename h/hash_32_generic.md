# Function: <code>hash_32_generic</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810639dd)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff8109ee7e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff810f7a12)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/dcache.c (ffffffff8124bb5a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff81298a60)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81331aa6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff813326b6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In lib/iommu-common.c (ffffffff8145af6a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff815ef2ba)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In net/core/dev.c (ffffffff81785e13)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/ipv4/route.c (ffffffff817c109b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee4b1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff817fe5df)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff818074e2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv6/addrconf.c (ffffffff8183ec35)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
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
In arch/x86/kernel/kvm.c (ffffffff81066e8d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810a3d5f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff811053b2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/dcache.c (ffffffff8125eb3a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff812ad4de)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81347846)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff81348456)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In lib/iommu-common.c (ffffffff81479a5a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161c48a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In net/core/dev.c (ffffffff817b33d3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff817deb6b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff817f069b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181eeb1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff8182f53f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81838572)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv6/addrconf.c (ffffffff81870845)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
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
In arch/x86/kernel/kvm.c (ffffffff8106615d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810a0ede)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff81107370)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff8126c50a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff812ba986)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8135c276)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8135cfc6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In lib/iommu-common.c (ffffffff81482daa)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff816304ca)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff8163cc41)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff817d1d21)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff817fe1a3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff81810ae3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183faf0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81850a2b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff818599c2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv6/addrconf.c (ffffffff81895615)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In arch/x86/kernel/kvm.c (ffffffff81069fad)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810a7733)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff811124a0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff8128e69a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff812de266)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81380f76)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff81381cc6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In lib/iommu-common.c (ffffffff814bedf5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_pool_init
```
```
In drivers/nvdimm/region_devs.c (ffffffff81698cfa)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff816a5911)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff8184bf81)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8187bdc3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff8188ff47)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bee90)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff818d0662)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff818d98c2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv6/addrconf.c (ffffffff81916ac9)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191b8df)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff8106cdb5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810ae2b5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8111de8f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812b4915)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff8130a4a6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff813ae5e2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff813b0ab6)
Location: include/linux/hash.h:68
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d4fa4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff816e1ce1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff818962ff)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff818ce5db)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff818e2e94)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914a6a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81926be4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81930302)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv6/addrconf.c (ffffffff8196e16a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819735f9)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81072f85)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810b7376)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8112962f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812c9b95)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff8131fc86)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff813c77d2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff813ca1b6)
Location: include/linux/hash.h:68
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f6ca0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81705101)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff818b856f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff818f982b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff8190fd34)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194321a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81955c94)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff8195f7e2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_dec_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff8199400c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819a3cea)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a9249)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81076b15)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810bc6cc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff811340bc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812e65a5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff813474f4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff813f2391)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff813f4d36)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff814991d8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff814996b1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff8173271d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff8173ef59)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81904741)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8195909b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/ipv4/route.c (ffffffff81972334)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a77d8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff819ba677)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff819c4672)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81a0026d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a10030)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a16079)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81077b65)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810c341c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8114005c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812f8105)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff8135f664)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8140c291)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8140ec06)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff814b3108)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff814b35d1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff817565cd)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81763139)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81936db1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8198f53b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81999496)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819a8ca4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de858)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff819f1207)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff819fb212)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81a36e50)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a46d73)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a4ccb9)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff8107efe5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/workqueue.c (ffffffff810cae16)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff8114fccc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In fs/dcache.c (ffffffff81330e65)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff813a5240)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8145b3b6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8145c776)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff814c0bce)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff81512548)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:uid_permitted_for_cred
```
```
In security/safesetid/securityfs.c (ffffffff81512a7b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:verify_ruleset
```
```
In drivers/nvdimm/region_devs.c (ffffffff81815bad)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81822f9a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81a01f7b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81a6741b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a6e2b8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/route.c (ffffffff81a93564)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb940)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv4/devinet.c (ffffffff81adf177)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81ae9b47)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81b2c0ed)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3dc53)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/route.c (ffffffff81b433ee)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
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
In arch/x86/kernel/kvm.c (ffffffff8107ec15)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/workqueue.c (ffffffff810c5f46)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff8114bf50)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In fs/dcache.c (ffffffff8133c7f5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff813b5fa0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81477706)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff814784a6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff814de64e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff8152f3e5)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/securityfs.c (ffffffff8152f9e8)
Location: include/linux/hash.h:68
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824d9d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81831cda)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81a025bb)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81a6fb3b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a771f5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/route.c (ffffffff81a9d414)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7901)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv4/devinet.c (ffffffff81aebf77)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81af69e7)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81b3ab12)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b4c7d3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/route.c (ffffffff81b51ade)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
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
In arch/x86/kernel/kvm.c (ffffffff8107f8a5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff810c7884)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff8114d402)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff81342c75)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e755)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
```
```
In fs/mbcache.c (ffffffff813bd0f0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8147d186)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8147df16)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff814e4fce)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff81535675)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/securityfs.c (ffffffff81535af8)
Location: include/linux/hash.h:68
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff8180812e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81814f0a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff819e912b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81a5842b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a5ec55)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99e30)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2a99)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81ad75e7)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81ae2132)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81b287f2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3a4a6)
Location: include/linux/hash.h:68
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108e685)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/workqueue.c (ffffffff810da5e4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/time/posix-timers.c (ffffffff81170bc2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff813906b5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb835)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
```
```
In fs/mbcache.c (ffffffff8140ce8f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff814d4906)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff814d56b6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/selinux/ss/sidtab.c (ffffffff8153e644)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
  - security/selinux/ss/sidtab.c:context_to_sid
```
```
In security/safesetid/lsm.c (ffffffff81593c44)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/securityfs.c (ffffffff815940f8)
Location: include/linux/hash.h:68
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff818928cb)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff8189f67a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81a99f5b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
```
In net/sched/sch_api.c (ffffffff81b1140e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81b17e25)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b552a0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8145b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81b96097)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81ba18da)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8c1d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_find_info
  - net/ipv4/fib_semantics.c:fib_find_info
```
```
In net/ipv6/anycast.c (ffffffff81bee7b5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81c00c46)
Location: include/linux/hash.h:68
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/workqueue.c (ffff80001012122c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffff8000101ab928)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffff8000103a56a8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffff8000104252bc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffff8000104ed0a4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffff8000104efa38)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffff8000105aad0c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffff8000105ab2a8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffff800010957a50)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffff800010963960)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffff800010bd5554)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffff800010c3b410)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffff800010c461ac)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffff800010c598dc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffff800010c925c0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffff800010ca7494)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffff800010cb2db8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffff800010cf7bd8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d09930)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d0fc18)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In kernel/workqueue.c (c0371024)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (c037fa68)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (c03a6560)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/time/posix-timers.c (c03f5778)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/cgroup/cgroup.c (c152518c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c0436cec)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (c04547ec)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:ftrace_find_profiled_func
```
```
In kernel/events/core.c (c04d0c50)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (c04ddfd8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/highmem.c (c0515f04)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - mm/highmem.c:set_page_address
```
```
In mm/ksm.c (c0547b78)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In fs/dcache.c (c0588eb0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/crypto/keysetup_v1.c (c05dc06c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (c05e2dec)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/mbcache.c (c05ede44)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/kernfs/dir.c (c0614598)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (c06946e0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/inode.c (c06abfe0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (c06ad068)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In fs/fat/namei_vfat.c (c06ad7e8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (c06ba750)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (c06c1560)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (c06d8a7c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (c0735c84)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/safesetid/lsm.c (c075a904)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (c075ae54)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/integrity/ima/ima_queue.c (c075d558)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (c078b8c8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In drivers/dax/super.c (c0a39b84)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (c0cf01b8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/core/bpf_sk_storage.c (c0d47db0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/sched/sch_api.c (c0d4d1c4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (c0d56020)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (c0d681c8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (c0da06d4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (c0da77a4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/devinet.c (c0db3ba8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (c0dbe844)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (c0dfe128)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e0ff98)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e17268)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
```
```
In lib/vsprintf.c (c0e92de4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/powerpc/kernel/iommu.c (c0000000013505c0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:setup_iommu_pool_hash
```
```
In kernel/workqueue.c (c00000000016a7c4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (c00000000020db10)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (c0000000004a10f8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (c000000000534534)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (c00000000062d35c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (c00000000062e89c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In security/safesetid/lsm.c (c000000000728880)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (c00000000072900c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (c000000000a05cbc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (c000000000a18d8c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1d2dc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:init_powernv_pstates
```
```
In net/core/dev.c (c000000000cb4a44)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (c000000000d34564)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (c000000000d40bc4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (c000000000d5a1cc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (c000000000da1e80)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (c000000000dbbc90)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (c000000000dc9f34)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (c000000000e1e5d4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e34198)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e3d474)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In kernel/workqueue.c (ffffffe0000da130)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffe000135804)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffe00026c260)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffe0002c43cc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffe00035d1fc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffe00035f852)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffe0003f39ac)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffe0003f3d7e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c698c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffe0005d04c6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffe00075ef0a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffe0007ac0b0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffe0007b3626)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/route.c (ffffffe0007c255a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1a78)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffe0008025d6)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffe00080b1a2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffe000842e42)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe000851570)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085778c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81076b65)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810bd78c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8113880c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812f06e5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff81357c44)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81404871)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff814071e6)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff814ab6e8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff814abbb1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170acbd)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff81717829)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff818d6d81)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8192f3ab)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81939306)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff81948b14)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e6c8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81990fa7)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff8199afb2)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff819d64e0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e6403)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ec349)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81066ae5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810abfbc)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8112b25c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812e1315)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff813488f4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff813f52f1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff813f7c66)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff8149c108)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff8149c5d1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff816de73d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff816efd59)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/net/vxlan.c (ffffffff81770e88)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:vxlan_find_sock
```
```
In net/core/dev.c (ffffffff81890bc1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff818e8eab)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818f2e06)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff81902604)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938188)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff8194aa67)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81954a72)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966816)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_find
  - net/ipv4/ip_tunnel.c:ip_tunnel_add
  - net/ipv4/ip_tunnel.c:ip_tunnel_lookup
  - net/ipv4/ip_tunnel.c:ip_tunnel_lookup
```
```
In net/ipv6/anycast.c (ffffffff819932a0)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819a31c3)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a9109)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81076b15)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810bccec)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8113652c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff812ee4f5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff81355714)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff81401bf1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff81404566)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff814a7788)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff814a7c51)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff81749a8d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff817565f9)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81927db1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff8198053b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff8198a496)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819b32e4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8e98)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff819fb847)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81a05852)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81a40f60)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a50e83)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a56dc9)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
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
In arch/x86/kernel/kvm.c (ffffffff81078585)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/workqueue.c (ffffffff810c506c)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/time/posix-timers.c (ffffffff8114302b)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/dcache.c (ffffffff813004b5)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/mbcache.c (ffffffff81368d06)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/fat/inode.c (ffffffff8141643f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffff8141a1da)
Location: include/linux/hash.h:68
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff814c0107)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/lsm.c:setuid_policy_lookup
```
```
In security/safesetid/securityfs.c (ffffffff814c05e1)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764f0d)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/dax/super.c (ffffffff8177185a)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81949481)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
```
In net/sched/sch_api.c (ffffffff819a2aab)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff819ab81e)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/route.c (ffffffff819bc9b4)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2bf8)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/devinet.c (ffffffff81a05b77)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81a0fe22)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:__ip_mc_dec_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv6/anycast.c (ffffffff81a4cb6f)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a5cdad)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a62e79)
Location: include/linux/hash.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
```
</details>
</li>
</ul>

## Differences
