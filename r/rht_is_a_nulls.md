# Function: <code>rht_is_a_nulls</code>

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
In lib/rhashtable.c (ffffffff8140088f)
Location: include/linux/rhashtable.h:189
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174cd5e)
Location: include/linux/rhashtable.h:189
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In security/apparmor/apparmorfs.c (0)
Location: include/linux/rhashtable.h:189
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:189
Inline: True
```
```
In lib/rhashtable.c (ffffffff814483b7)
Location: include/linux/rhashtable.h:189
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b9138)
Location: include/linux/rhashtable.h:189
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In security/apparmor/apparmorfs.c (0)
Location: include/linux/rhashtable.h:206
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:206
Inline: True
```
```
In lib/rhashtable.c (ffffffff81466c4f)
Location: include/linux/rhashtable.h:206
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e8b6c)
Location: include/linux/rhashtable.h:206
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5322)
Location: include/linux/rhashtable.h:206
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In security/apparmor/apparmorfs.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146bb40)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8180819a)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c2b8)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb5de)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff81497e30)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:220
Inline: True
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
In ipc/util.c (ffffffff813d6d51)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81432f65)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8143efeb)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cc4ea)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818ba8cf)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d65ab)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dc014)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8193919f)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81942209)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81944d1a)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/ip6mr.c (ffffffff8199e95c)
Location: include/linux/rhashtable.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9db1)
Location: include/linux/rhashtable.h:221
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
In kernel/bpf/offload.c (ffffffff811df466)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f134d)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fc41)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf00)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e0c7a)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e180b)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901992)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819089e1)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d6c)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81972006)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81974e7e)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fefe)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d52fb)
Location: include/linux/rhashtable.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e08d3)
Location: include/linux/rhashtable.h:92
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
In kernel/bpf/offload.c (ffffffff811f4e63)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d618)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce7b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488dc5)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150c939)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8193006b)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff819629f6)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81969cc2)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfad3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db958)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819de9f5)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c8e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44132)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f536)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff81201e73)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437468)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81496b4b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c75)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152a789)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819622cb)
Location: include/linux/rhashtable.h:108
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
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963eee)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819a0732)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06663)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12888)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15aa5)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20cde)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ad22)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a861c6)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff81228e95)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In ipc/util.c (ffffffff814866b8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff814eed47)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf59)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158efc1)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a36406)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a78714)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af601d)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01dfd)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0660f)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b70)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b7538d)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b816a1)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff81230a79)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c98)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c1bc)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a169)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff815abb31)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a384fd)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81a1e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e8d)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fedd)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b147ff)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b210f0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b840fd)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90ebf)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff81234c24)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c93)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81512b47)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a78)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b601b)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f334)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6ab15)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee784)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afdacd)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b025fb)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ed1b)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d7d)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b800ba)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff8126ed40)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81502143)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81570747)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec18)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c4e9)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad35d0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b24115)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeb40)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfbdc)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc456b)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd211b)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a7f0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d2cc)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b96a)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/bpf/offload.c (ffffffff812be5f6)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593764)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c5ad)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d712)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9cac)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c51128)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac018)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d420e4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d55e33)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595ed)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d686bf)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd867b)
Location: include/linux/rhashtable.h:108
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
In net/ipv6/ip6mr.c (ffffffff81ddb547)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb34b)
Location: include/linux/rhashtable.h:108
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
In kernel/bpf/offload.c (ffffffff81321294)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d16b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In ipc/util.c (ffffffff8163c1b4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec91)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11c7)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9e7c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e05de1)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69bec)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af24)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f20567)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a2d)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3375f)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa08b)
Location: include/linux/rhashtable.h:108
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
In net/ipv6/ip6mr.c (ffffffff81fae14b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef3b)
Location: include/linux/rhashtable.h:108
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
In kernel/bpf/offload.c (ffffffff81351a39)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dffd)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In ipc/util.c (ffffffff81674782)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7753)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0d7)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff818191fc)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78ae3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b86)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa64)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f80055)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f8357d)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92adf)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a9d2)
Location: include/linux/rhashtable.h:108
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
In net/ipv6/ip6mr.c (ffffffff8200e8e9)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb90)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82093653)
Location: include/linux/rhashtable.h:108
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
In kernel/bpf/offload.c (ffffffff81378f19)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a725d)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In ipc/util.c (ffffffff816b0b42)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff817344c6)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bd7)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e54c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f389b3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f88de6)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82031114)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff820466d5)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff82049c2d)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d143)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d99a2)
Location: include/linux/rhashtable.h:108
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
In net/ipv6/ip6mr.c (ffffffff820dd879)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eecc0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169f03)
Location: include/linux/rhashtable.h:108
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
In kernel/bpf/offload.c (ffff80001028a234)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc7c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffff80001058cd44)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff8000105989e0)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffff8000106361b0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06594)
Location: include/linux/rhashtable.h:108
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
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c086d0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4edfc)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf4bc)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf6c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffff800010cd165c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde700)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b88)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51eb0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (c04b98c8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da0b8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c073da28)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (c0749c18)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (c07dc0f0)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f650)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20de8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5e004)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcae34)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d94)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/ipmr_base.c (c0ddb52c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6b44)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47054)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f68)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (c0000000003355f8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000667048)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c0000000006fed90)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070f950)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (c0000000007db798)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0a64)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2cb8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4d4a4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda130)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb468)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (c000000000def80c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe900)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79690)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa7c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffe0001be380)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe0003854a4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db032)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5324)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004633d4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784b2e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078649c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007bab7c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe00081527c)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082092a)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffe000822c10)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dc50)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f5aa)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a584)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811fa493)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa48)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f12b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b255)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff81522d69)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8190229b)
Location: include/linux/rhashtable.h:108
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
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903ebe)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819405a2)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6403)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2148)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5135)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c036e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a3b2)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25856)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811ed1e3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814204c8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fb4b)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc75)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513049)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bc0cb)
Location: include/linux/rhashtable.h:108
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
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcee)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818fa092)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fec3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e778)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81971765)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d15e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7172)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2616)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811f8263)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bbe8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b1cb)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814972f5)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151edf9)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819532cb)
Location: include/linux/rhashtable.h:108
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
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954eee)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81991732)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ca3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9e8)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f9d5)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2adee)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e32)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a902d6)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff812065c9)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442bfb)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff814a30c0)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3d4)
Location: include/linux/rhashtable.h:108
Inline: True
```
```
In lib/rhashtable.c (ffffffff81538814)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81974dd3)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819766a4)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b41be)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b586)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a279ab)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2aed5)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3641e)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a917b5)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d54a)
Location: include/linux/rhashtable.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
</details>
</li>
</ul>

## Differences
