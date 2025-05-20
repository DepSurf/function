# Function: <code>rht_head_hashfn</code>

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
In lib/rhashtable.c (ffffffff814008b2)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174cc80)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_release
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
In security/apparmor/policy_unpack.c (ffffffff813bc01e)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814482d1)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b9fdd)
Location: include/linux/rhashtable.h:242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In security/apparmor/policy_unpack.c (ffffffff813d353f)
Location: include/linux/rhashtable.h:259
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81466879)
Location: include/linux/rhashtable.h:259
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e9960)
Location: include/linux/rhashtable.h:259
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5102)
Location: include/linux/rhashtable.h:259
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In security/apparmor/policy_unpack.c (ffffffff813e663a)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146c0d5)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8180964b)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186b23f)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb64)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In ipc/util.c (ffffffff813a7234)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d81c)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814983d5)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882ada)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff8188859c)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818eb9ed)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950904)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In ipc/util.c (ffffffff813d6772)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef63)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cd5c0)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818bad3c)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d64f3)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818dbfbe)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8193912e)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8194219f)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199e8f2)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e06)
Location: include/linux/rhashtable.h:282
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0e02)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be79)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e17bd)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e1dd9)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff819018dd)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8190898e)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81968cfe)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971f9f)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fbde)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5294)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0931)
Location: include/linux/rhashtable.h:148
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cf28)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d4d)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d6ea)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8193074c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8196297d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969c58)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa4d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db8de)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98ac)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440b5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f585)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436d78)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2bfd)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b53a)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81962c5e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963e69)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a06c8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a065dd)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1280e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a215c0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7aca5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86215)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int rht_head_hashfn(struct rhashtable *ht, const struct bucket_table *tbl, const struct rhash_head *he, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812291ed)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff8148685d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcedf)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158df50)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a35f2d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a7917f)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e1d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b00b30)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1089a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b74020)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8138d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff8158df50-ffffffff8158dfa6: rht_head_hashfn (STB_LOCAL)
ffffffff81b00b30-ffffffff81b00b86: rht_head_hashfn (STB_LOCAL)
ffffffff81b74020-ffffffff81b74076: rht_head_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int rht_head_hashfn(struct rhashtable *ht, const struct bucket_table *tbl, const struct rhash_head *he, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230d82)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff814a3f25)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a0f3)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aaae0)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a38315)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81fa4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02ca5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0ec10)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1eb8a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b82d90)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90be5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff815aaae0-ffffffff815aab36: rht_head_hashfn (STB_LOCAL)
ffffffff81b0ec10-ffffffff81b0ec66: rht_head_hashfn (STB_LOCAL)
ffffffff81b82d90-ffffffff81b82de6: rht_head_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int rht_head_hashfn(struct rhashtable *ht, const struct bucket_table *tbl, const struct rhash_head *he, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234f32)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff814a9e59)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a0a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b5700)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f159)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b098)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5a9)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afc900)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c81a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b71a10)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fdf9)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff815b5700-ffffffff815b576c: rht_head_hashfn (STB_LOCAL)
ffffffff81afc900-ffffffff81afc96c: rht_head_hashfn (STB_LOCAL)
ffffffff81b71a10-ffffffff81b71a7c: rht_head_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int rht_head_hashfn(struct rhashtable *ht, const struct bucket_table *tbl, const struct rhash_head *he, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126f062)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff81502309)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebaa)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161bb60)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad33e9)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b246b8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae959)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbe080)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa0a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a140)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bec0)
Location: include/linux/rhashtable.h:164
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b699)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff8161bb60-ffffffff8161bbcc: rht_head_hashfn (STB_LOCAL)
ffffffff81bbe080-ffffffff81bbe0ec: rht_head_hashfn (STB_LOCAL)
ffffffff81c3bec0-ffffffff81c3bf2c: rht_head_hashfn (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff812bdfc8)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff81593969)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d68a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea1ed)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c50cac)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabf57)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41871)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55d6e)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d680e0)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7ea7)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb415)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deadce)
Location: include/linux/rhashtable.h:164
Inline: True
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
In kernel/bpf/offload.c (ffffffff81321657)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d503)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff8163c4fc)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d113a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da408)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e0634c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69b27)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a68a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2049e)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33170)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa98a1)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae015)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe9ae)
Location: include/linux/rhashtable.h:164
Inline: True
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
In kernel/bpf/offload.c (ffffffff813511b8)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e450)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff81674979)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a04a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8181971a)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78bdc)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5ab8)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a1ba)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7ff96)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f924f0)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a221)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e7bc)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f843)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/handshake/request.c (ffffffff82092b60)
Location: include/linux/rhashtable.h:164
Inline: True
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
In kernel/bpf/offload.c (ffffffff81378618)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a76b0)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In ipc/util.c (ffffffff816b0d39)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747b4a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185ea6a)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38aac)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88d08)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203086a)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82046616)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060260)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d91c2)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd74c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee973)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In net/handshake/request.c (ffffffff82169410)
Location: include/linux/rhashtable.h:164
Inline: True
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d3f0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff80001059893c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffff800010636b04)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06760)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08588)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4ed88)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf42c)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbe90)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd28)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44a40)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51de8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d9820)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749b6c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (c07dc9a0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f8e0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d216c8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5ee80)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcad9c)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7cf8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7a10)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e46fb8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52ed0)
Location: include/linux/rhashtable.h:164
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
In kernel/bpf/offload.c (c000000000335510)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666554)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f8a8)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (c0000000007dc9dc)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0cc0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2bb4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d420)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda08c)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb380)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfccd0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79500)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a9a0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384cd0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52ba)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640b4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784cc8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007863c4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bab22)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815210)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082080c)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0c4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3ce)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4ac)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f358)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b1dd)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523b1a)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902c2e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e39)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81940538)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a637d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b20ce)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c50)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a335)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258a5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fdd8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bbfd)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513dfa)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bca5e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdc69)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa028)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe3d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e6fe)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da40)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d70f5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2665)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b4f8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149727d)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fbaa)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81953c5e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954e69)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819916c8)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c1d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c96e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b6d0)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84db5)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90325)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8144245b)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af34c)
Location: include/linux/rhashtable.h:164
Inline: True
```
```
In lib/rhashtable.c (ffffffff815394a3)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819753e4)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976e0e)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b414d)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b4f1)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2792a)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d18)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91731)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf24)
Location: include/linux/rhashtable.h:164
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
