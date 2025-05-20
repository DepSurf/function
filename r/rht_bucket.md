# Function: <code>rht_bucket</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813db62e)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In lib/rhashtable.c (ffffffff8146b306)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff818087b4)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8186affe)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbafb)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In ipc/util.c (ffffffff813a7920)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814020df)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In lib/rhashtable.c (ffffffff814975f6)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff8188275e)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81887634)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818eb79e)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff8195089b)
Location: include/linux/rhashtable.h:411
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In ipc/util.c (ffffffff813d6d38)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81432f4c)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In lib/rhashtable.c (ffffffff814cc4d1)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818ba8b5)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d5dae)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dad04)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81939311)
Location: include/linux/rhashtable.h:427
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81944d01)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9d97)
Location: include/linux/rhashtable.h:427
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811df37b)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f1326)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fc28)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In lib/rhashtable.c (ffffffff814e0c61)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e17e6)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff818ff066)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819075e1)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968ed2)
Location: include/linux/rhashtable.h:288
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81974e5d)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fedb)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e08b0)
Location: include/linux/rhashtable.h:288
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811f4d55)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d5e0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce3d)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150c910)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81930038)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8195f865)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81968893)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfdb0)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819de9c3)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c5a)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f508)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81201d65)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437430)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81496b0d)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152a760)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81962298)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff819639b5)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199f333)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06940)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15a73)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20caa)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86198)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81228e6a)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In ipc/util.c (ffffffff81486689)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff814eed11)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158eea8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a363df)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
```
```
In net/netlink/af_netlink.c (ffffffff81a786e8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6376)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b065e5)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b45)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81676)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81230a4f)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c6c)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c186)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aba18)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a37bcb)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a819f7)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81b031e6)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b147d5)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b210c5)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90e9a)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81234bfb)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c68)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81512b12)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b5efa)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a1ed57)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6aaf8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee995)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b025d1)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ecf1)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80099)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff8126ed17)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81502118)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81570712)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c3a9)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81ad2df7)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b240f8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81baed65)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4541)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd20f1)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a7c6)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b949)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff812be5c8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593736)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c584)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9b23)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81c51103)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac752)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d420bb)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595c2)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68694)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd865e)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb32a)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81321269)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d140)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In ipc/util.c (ffffffff8163c186)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec68)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9ce3)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81e05dc0)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6a352)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0aefb)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a02)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33734)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa06e)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef1a)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81351a0c)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dfd0)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In ipc/util.c (ffffffff81674754)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7727)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819063)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81e78ac6)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec631e)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa3b)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83552)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92ab4)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a9b5)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb6b)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff8209362a)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_hash_lookup
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
In kernel/bpf/offload.c (ffffffff81378eec)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7230)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In ipc/util.c (ffffffff816b0b14)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8173449a)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e3b3)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81f38996)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f8958f)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820310eb)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff82049c02)
Location: include/linux/rhashtable.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d119)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d9985)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eec9b)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169eda)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_hash_lookup
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
In kernel/bpf/offload.c (ffff80001028a690)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc4c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffff80001058cd1c)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffff800010636184)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffff800010c0656c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffff800010c07f4c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4ce8c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf7d8)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1634)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6d0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52724)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (c04b9758)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da090)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c073da08)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (c07dc0cc)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (c0d1f628)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c0d20dc8)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dfe4)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c0dcb1b4)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (c0ddb50c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6b1c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c0e52ab8)
Location: include/linux/rhashtable.h:287
Inline: True
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
In kernel/bpf/offload.c (c00000000033614c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c00000000066701c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c0000000006fed64)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (c0000000007db768)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (c000000000cf0a38)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2338)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4bc74)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda584)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (c000000000def7e0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe8d8)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ad8c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffe0001be6c6)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe00038546a)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db004)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffe00046337c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffe000784b02)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffe000785ff4)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9d74)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe0008154b4)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffe000822be0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dc20)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a75c)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811fa385)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa10)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f0ed)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff81522d40)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81902268)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81903985)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193f1a3)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a66e0)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5103)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c033a)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25828)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811ed0d5)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81420490)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fb0d)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513020)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff818bc098)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff818bd7b5)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f8ca3)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819601a0)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81971733)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d12a)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e25e8)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811f8155)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bbb0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b18d)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151edd0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81953298)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff819549b5)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81990333)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10f80)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f9a3)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2adba)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a902a8)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff812064aa)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442bc5)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3082)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In lib/rhashtable.c (ffffffff815387eb)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81974da0)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (ffffffff81976672)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2c23)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b8e3)
Location: include/linux/rhashtable.h:287
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2aea3)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a363e9)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d519)
Location: include/linux/rhashtable.h:287
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
</details>
</li>
</ul>

## Differences
