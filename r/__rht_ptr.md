# Function: <code>__rht_ptr</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4e4e)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d603)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce66)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488db0)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150c927)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81930056)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff819629e1)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81969cad)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfaba)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db943)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819de9e1)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c77)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a4411d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f522)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff81201e5e)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437453)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff81496b36)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c60)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152a777)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819622b6)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffff81963ed9)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819a071d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0664a)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12873)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15a91)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20cc7)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ad0d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a861b2)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff81228e8c)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In ipc/util.c (ffffffff814866ab)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff814eed3e)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf47)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158eeb8)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a363fe)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a7870b)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e9f)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01cd7)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06606)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b67)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b75267)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81698)
Location: include/linux/rhashtable.h:351
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
In kernel/bpf/offload.c (ffffffff81230a70)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c8f)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c1b3)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a157)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aba28)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (ffffffff81a3837f)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81a16)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02d0f)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fdb7)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b147f6)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b210e7)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fd7)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90eb7)
Location: include/linux/rhashtable.h:351
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
In kernel/bpf/offload.c (ffffffff81234c1b)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c8a)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff81512b3e)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a66)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b5f0a)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f1c3)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6ab0d)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee613)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd9a9)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81b025f2)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ed12)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c59)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b800b2)
Location: include/linux/rhashtable.h:351
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
In kernel/bpf/offload.c (ffffffff8126ed37)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8150213a)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/apparmorfs.c (ffffffff8157073e)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec06)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c3b9)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad3453)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b2410d)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9c3)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfaa9)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4562)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2112)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a7e7)
Location: include/linux/rhashtable.h:351
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
In net/ipv6/ip6mr.c (ffffffff81c3d199)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b962)
Location: include/linux/rhashtable.h:351
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
In kernel/bpf/offload.c (ffffffff812be5ea)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593758)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c5a5)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d700)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9b37)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c51120)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac006)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d420d8)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d55e21)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595e4)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d686b7)
Location: include/linux/rhashtable.h:351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd8673)
Location: include/linux/rhashtable.h:351
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
In net/ipv6/ip6mr.c (ffffffff81ddb535)
Location: include/linux/rhashtable.h:351
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb343)
Location: include/linux/rhashtable.h:351
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
In kernel/bpf/offload.c (ffffffff8132128b)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d162)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In ipc/util.c (ffffffff8163c1a8)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec89)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11b5)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9cf7)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e05dd9)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69bda)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af18)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f20555)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a24)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33757)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa083)
Location: include/linux/rhashtable.h:358
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
In net/ipv6/ip6mr.c (ffffffff81fae139)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef33)
Location: include/linux/rhashtable.h:358
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
In kernel/bpf/offload.c (ffffffff81351a2d)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dff1)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In ipc/util.c (ffffffff81674776)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f774b)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0c5)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819077)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78adb)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b74)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa5c)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f80043)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83574)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92ad7)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a9ca)
Location: include/linux/rhashtable.h:358
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
In net/ipv6/ip6mr.c (ffffffff8200e8d7)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb88)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff8209364a)
Location: include/linux/rhashtable.h:358
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
In kernel/bpf/offload.c (ffffffff81378f0d)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7251)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In ipc/util.c (ffffffff816b0b36)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff817344be)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bc5)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e3c7)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f389ab)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f88dd4)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203110c)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff820466c3)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff82049c24)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d13a)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d999a)
Location: include/linux/rhashtable.h:358
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
In net/ipv6/ip6mr.c (ffffffff820dd867)
Location: include/linux/rhashtable.h:358
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eecb8)
Location: include/linux/rhashtable.h:358
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169efa)
Location: include/linux/rhashtable.h:358
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
In kernel/bpf/offload.c (ffff80001028a220)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc64)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffff80001058cd30)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff8000105989cc)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffff8000106361a0)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06580)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffff800010c086bc)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4ede8)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf4a4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf58)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1648)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6e8)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b74)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e9c)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (c04b98b4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da0a4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c073da14)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (c0749c04)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (c07dc0dc)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f63c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20dd4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dff0)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcae34)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d80)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/ipmr_base.c (c0ddb518)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6b30)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47040)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f54)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (c0000000003355e0)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000667030)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (c0000000006fed78)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070f93c)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (c0000000007db780)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0a4c)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (c000000000cf2ca0)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4d48c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda11c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb450)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (c000000000def7f4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe8ec)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79678)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa64)
Location: include/linux/rhashtable.h:352
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be370)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe000385488)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db01e)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5318)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004633c4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784b1a)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffe00078648c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007bab6c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe00081526c)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082091a)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffe000822bfa)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dc38)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f59a)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a574)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff811fa47e)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa33)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f116)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b240)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff81522d57)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902286)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffff81903ea9)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8194058d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63ea)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2133)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5121)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0357)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a39d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25842)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff811ed1ce)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814204b3)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fb36)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc60)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513037)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bc0b6)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffff818bdcd9)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818fa07d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8195feaa)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e763)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81971751)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d147)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d715d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2602)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff811f824e)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bbd3)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b1b6)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814972e0)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151ede7)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819532b6)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffff81954ed9)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199171d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c8a)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9d3)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f9c1)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2add7)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e1d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a902c2)
Location: include/linux/rhashtable.h:352
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
In kernel/bpf/offload.c (ffffffff812065b4)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442be7)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (ffffffff814a30ab)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3bf)
Location: include/linux/rhashtable.h:352
Inline: True
```
```
In lib/rhashtable.c (ffffffff81538802)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81974dbe)
Location: include/linux/rhashtable.h:352
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
In net/core/flow_offload.c (ffffffff81976690)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b41a9)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b56d)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27996)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2aec1)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36406)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a917a0)
Location: include/linux/rhashtable.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d536)
Location: include/linux/rhashtable.h:352
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
