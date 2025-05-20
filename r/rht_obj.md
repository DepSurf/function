# Function: <code>rht_obj</code>

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
In lib/rhashtable.c (ffffffff813ffe08)
Location: include/linux/rhashtable.h:199
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174beac)
Location: include/linux/rhashtable.h:199
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
In security/apparmor/apparmorfs.c (ffffffff813ae44a)
Location: include/linux/rhashtable.h:199
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc059)
Location: include/linux/rhashtable.h:199
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81447786)
Location: include/linux/rhashtable.h:199
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b9fdd)
Location: include/linux/rhashtable.h:199
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
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
In security/apparmor/apparmorfs.c (ffffffff813c525b)
Location: include/linux/rhashtable.h:216
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813d353f)
Location: include/linux/rhashtable.h:216
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814660ae)
Location: include/linux/rhashtable.h:216
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e9960)
Location: include/linux/rhashtable.h:216
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a50b2)
Location: include/linux/rhashtable.h:216
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In security/apparmor/apparmorfs.c (ffffffff813db584)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff813e663a)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146b32e)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8180964b)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8186b020)
Location: include/linux/rhashtable.h:230
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
In net/ipv6/seg6_hmac.c (ffffffff818cbb1e)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (ffffffff813a7943)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81402030)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d81c)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8149761e)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882af7)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8188859c)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818eb7c0)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff819508be)
Location: include/linux/rhashtable.h:230
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (ffffffff813d6d82)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81432e9e)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef63)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cc510)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818ba8e0)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d64f3)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dbfbe)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8193912e)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8194219f)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81944d34)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/ip6mr.c (ffffffff8199e8f2)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9dc9)
Location: include/linux/rhashtable.h:231
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f1382)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fb6d)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be79)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e0ca0)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e1828)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff819018dd)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8190898e)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968cfe)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971f9f)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81974e98)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ff13)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5294)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e08fc)
Location: include/linux/rhashtable.h:97
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d637)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147cd7c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d4d)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150c959)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81930074)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8196297d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81969c58)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa4d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db8de)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819dea14)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c98)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440b5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f53f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437487)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81496a4c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2bfd)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152a7a9)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819622d4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963e69)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819a06c8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a065dd)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1280e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15ac4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20ce8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7aca5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a861cf)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff812294ee)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814866e0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff814eec47)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcedf)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158efef)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a36416)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a7872d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e1d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b00b40)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06623)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b8c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b74030)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b816be)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff81231039)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3cb3)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c0b7)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a0f3)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff815abb5f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a38315)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81a30)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02ca5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0ec24)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14813)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2110c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b82da4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90ed3)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff812351c9)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9cae)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81512a47)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a0a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b604b)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81a1f159)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6ab28)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5a9)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afc920)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0260f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ed37)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b71a30)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b800cf)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff8126f30b)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8150215e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81570647)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebaa)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c535)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_head_hashfn
```
```
In net/core/xdp.c (ffffffff81ad33e9)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b24128)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae959)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbe0a0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:rht_head_hashfn
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc457f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2137)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a80a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bee0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:rht_head_hashfn
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b97f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff812be61d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593781)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c4b6)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d68a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9cfa)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c51140)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cabf57)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d420fb)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d55d6e)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595fc)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d686de)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd868e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb415)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb362)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81321900)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d191)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In ipc/util.c (ffffffff8163c1d1)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816beba0)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d113a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9eca)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e05df4)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69b27)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af3b)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f2049e)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a3c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3377e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa09e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae015)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef52)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81351a63)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e033)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In ipc/util.c (ffffffff816747a0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f765f)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a04a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8181924a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78af3)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec5ab8)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa89)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7ff96)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83593)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92afe)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a9e5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e7bc)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fba4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82093332)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_hash_lookup
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
In kernel/bpf/offload.c (ffffffff81378f43)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7293)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In ipc/util.c (ffffffff816b0b60)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff817343d2)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747b4a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e59a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f389c3)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f88d08)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82031139)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82046616)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff82049c43)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d15a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d99b5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd74c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eecd4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169be2)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_hash_lookup
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
In kernel/bpf/offload.c (ffff80001028a160)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc94)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffff80001058cd50)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff80001059893c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffff8000106361d8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c065a0)
Location: include/linux/rhashtable.h:113
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
In net/core/flow_offload.c (ffff800010c08588)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4ed88)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf42c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbe90)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1668)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde714)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44a40)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51dbc)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (c04b9830)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da0cc)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c073d90c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (c0749b6c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (c07dc118)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f660)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20e00)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5e018)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcad9c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7cf8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/ipmr_base.c (c0ddb544)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6b54)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e46fb8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52ed0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (c000000000335510)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000667060)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c0000000006feda0)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070f8a8)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (c0000000007db7d0)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0a6c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2bb4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4d420)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda08c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb380)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (c000000000def81c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe908)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79500)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a970)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffe0001be2b4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe0003854aa)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db03a)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52ba)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004633ee)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784b34)
Location: include/linux/rhashtable.h:113
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
In net/core/flow_offload.c (ffffffe0007863c4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007bab22)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe000815210)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082083a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffe000822c16)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dc58)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3fc)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a49c)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa67)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f02c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b1dd)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff81522d89)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819022a4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e39)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81940538)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a637d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b20ce)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5154)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0378)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a335)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2585f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814204e7)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fa4c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bbfd)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513069)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bc0d4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdc69)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818fa028)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe3d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e6fe)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81971784)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d168)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d70f5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e261f)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bc07)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b0cc)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149727d)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151ee19)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819532d4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954e69)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819916c8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c1d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c96e)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f9f4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2adf8)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84db5)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a902df)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442c1b)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff814a2fb7)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af34c)
Location: include/linux/rhashtable.h:113
Inline: True
```
```
In lib/rhashtable.c (ffffffff81538837)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81974ddc)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819766d6)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b414d)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b4f1)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2792a)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2aef4)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36427)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91731)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d568)
Location: include/linux/rhashtable.h:113
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
</details>
</li>
</ul>

## Differences
