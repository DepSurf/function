# Function: <code>rht_key_hashfn</code>

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
In lib/rhashtable.c (ffffffff81400a38)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174be38)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813ae418)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc18f)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8144849f)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b8cfc)
Location: include/linux/rhashtable.h:211
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813c5227)
Location: include/linux/rhashtable.h:228
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813d3713)
Location: include/linux/rhashtable.h:228
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146687b)
Location: include/linux/rhashtable.h:228
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e8796)
Location: include/linux/rhashtable.h:228
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5045)
Location: include/linux/rhashtable.h:228
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813db613)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6803)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146c0fa)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81808756)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8186afac)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbaa5)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (ffffffff813a7903)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff814020bf)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8140da0e)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814983f8)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882b03)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818875d6)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818eb74c)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950845)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (ffffffff813d6ce6)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81432f2d)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f7e1)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cd717)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818ba897)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d64ff)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818daca6)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81939263)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8194219f)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81944cdc)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/ip6mr.c (ffffffff8199e8f2)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9d43)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811df40a)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f12d9)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fc09)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c6da)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e190f)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e17ca)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff819018ea)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81907586)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968e30)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971f9f)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81974e3c)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197febb)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5294)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0863)
Location: include/linux/rhashtable.h:139
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811f4ded)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d58f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce1f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488ee6)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d872)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8193001f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8196297d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81968838)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfcae)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db8de)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819de99c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c3d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440b5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f4b5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff81201dfd)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814373df)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81496aef)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2d96)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b6c2)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8196227f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963e69)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199f2d8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0683e)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1280e)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15a4c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20c8d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7aca5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86145)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff81228e4a)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In ipc/util.c (ffffffff81486665)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff814eecf0)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd08f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158df96)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a363b6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a786c5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5f40)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b00b76)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b065c5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b1f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b74066)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81653)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff81230a31)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c48)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c165)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a2ae)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aab26)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a38420)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a819d5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02db0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0ec56)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b147b5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2109f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b82dd6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90e78)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff81234be1)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c48)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81512af5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520bb5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b574c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a1f264)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6aad5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee6b4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afc94c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b025b5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0eccf)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b71a5c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80078)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff8126ecfd)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff815020f8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff815706f5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ed55)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161bbac)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81ad34f4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b240d5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baea64)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbe0cc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4525)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd20cf)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a7a6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bf0c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b928)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff812be5b3)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8159371d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c562)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d877)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea423)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c510ec)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac6f8)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42096)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d55d78)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595a5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68674)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd863a)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb426)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb30b)
Location: include/linux/rhashtable.h:155
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
In kernel/bpf/offload.c (ffffffff81321252)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d124)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In ipc/util.c (ffffffff8163c16d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec47)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1332)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da641)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e05da2)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6a2f8)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0aed6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f204a8)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f239e5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33714)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa04a)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae026)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeefb)
Location: include/linux/rhashtable.h:155
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
In kernel/bpf/offload.c (ffffffff813519b6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137df73)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In ipc/util.c (ffffffff81674705)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f770b)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a22f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff818197cd)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78ab8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec62c7)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa16)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7ffa6)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83535)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92a94)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a994)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e7d2)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb1d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff820935d6)
Location: include/linux/rhashtable.h:155
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
In kernel/bpf/offload.c (ffffffff81378e96)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a71d3)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In ipc/util.c (ffffffff816b0ac5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8173447e)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747d2f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185eb1d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38988)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f89538)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820310c6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82046626)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff82049be5)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d0fd)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d9964)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd762)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eec4d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169e86)
Location: include/linux/rhashtable.h:155
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
In kernel/bpf/offload.c (ffff80001028a16c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dbd8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffff80001058ccfc)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff800010598b3c)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffff800010636c28)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06550)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08594)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4ce0c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf6b4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbea4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1614)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6a8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44a50)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51de8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (c04b9b48)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da06c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c073d9e4)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (c0749ddc)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (c07dc9b0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f600)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20da4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dfc0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcb084)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7fe4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/ipmr_base.c (c0ddb4e8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6af8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47334)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e530cc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (c000000000335524)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000666fa0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c0000000006fed30)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070fbb0)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcb44)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0a10)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2bcc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4bbe4)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda3f0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb394)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (c000000000def7ac)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe8b0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79518)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a9a0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffe0001be2a0)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe0003853e2)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffe0003dafee)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e545c)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640cc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784aee)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007863c8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9ce2)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe000815228)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082080c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffe000822bcc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dbfe)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3ce)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4ac)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811fa41d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142f9bf)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f0cf)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b376)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523ca2)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8190224f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e39)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193f148)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a65de)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b20ce)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819b50dc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c031d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a335)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a257d5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811ed16d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142043f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147faef)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bd96)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513f82)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bc07f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdc69)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f8c48)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8196009e)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e6fe)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff8197170c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d10d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d70f5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2595)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811f81ed)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bb5f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b16f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81497416)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fd32)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8195327f)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954e69)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819902d8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10e7e)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c96e)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f97c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ad9d)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84db5)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90255)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff8120654c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442b75)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3064)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af51f)
Location: include/linux/rhashtable.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffff81539634)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81974d87)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8197661b)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2bc8)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b7a6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2792a)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2ae7c)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a363c6)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91731)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d4cc)
Location: include/linux/rhashtable.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
</details>
</li>
</ul>

## Differences
