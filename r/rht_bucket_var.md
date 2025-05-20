# Function: <code>rht_bucket_var</code>

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
In lib/rhashtable.c (ffffffff8146b0ce)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81809689)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff8186b286)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbba1)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In ipc/util.c (ffffffff813a6f7d)
Location: include/linux/rhashtable.h:418
Inline: True
```
```
In lib/rhashtable.c (ffffffff814973ae)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff818828fd)
Location: include/linux/rhashtable.h:418
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818885da)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff818eba39)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950946)
Location: include/linux/rhashtable.h:418
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In ipc/util.c (ffffffff813d67b7)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In lib/rhashtable.c (ffffffff814cc5df)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818bad7e)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d6252)
Location: include/linux/rhashtable.h:434
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dbff8)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81939182)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819421ec)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/ip6mr.c (ffffffff8199e93f)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e49)
Location: include/linux/rhashtable.h:434
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811df44c)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff813f0e44)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In lib/rhashtable.c (ffffffff814e094f)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e1e18)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901596)
Location: include/linux/rhashtable.h:295
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819089c5)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d4f)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971fe9)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fc20)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d52de)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e096d)
Location: include/linux/rhashtable.h:295
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811f4e1b)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141cba1)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d5ea)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8193077c)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8196260d)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969c7e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf7ce)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db914)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98d1)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440ee)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5b3)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81201e2b)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814369f1)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b43a)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81962c89)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963b3d)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a06ee)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0635e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12844)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a208b2)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7acde)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86243)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff8122923e)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff814868ab)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff8158eaec)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a35f7b)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a791c6)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e6b)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01ca0)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12ffe)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b75230)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b813db)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff81230dce)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff814a3f5b)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff815ab64c)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a3834b)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81fd6)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02cdb)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fd80)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2140e)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fa0)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90c1b)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff81234f72)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff814a9e90)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff815b64b0)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f190)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b0c6)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5e0)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd972)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f01e)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c22)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fe30)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff8126f0a2)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff81502340)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff8161c9f3)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad3420)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b246e6)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae990)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa72)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd241e)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c39960)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d162)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b6d0)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff812be329)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff81593bbb)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea220)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c50ccb)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cadd54)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41c30)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d56492)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68117)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7640)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb8b0)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb09b)
Location: include/linux/rhashtable.h:293
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
In kernel/bpf/offload.c (ffffffff81321679)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d870)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff8163c51b)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da43e)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e0636b)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6b348)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0aa70)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20c74)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331a7)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa9020)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faead4)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbec9b)
Location: include/linux/rhashtable.h:293
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
In kernel/bpf/offload.c (ffffffff8135173c)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e4cc)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff81674c66)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819745)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78bee)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec7357)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a5a0)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80004)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92527)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820099a0)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200e898)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f8a6)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/handshake/request.c (ffffffff82092bdc)
Location: include/linux/rhashtable.h:293
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
In kernel/bpf/offload.c (ffffffff81378c1c)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a772c)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In ipc/util.c (ffffffff816b1026)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185ea95)
Location: include/linux/rhashtable.h:293
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38abe)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8a697)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030c50)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82046684)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060297)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d8940)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dd828)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee9d6)
Location: include/linux/rhashtable.h:293
Inline: True
```
```
In net/handshake/request.c (ffffffff8216948c)
Location: include/linux/rhashtable.h:293
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
In kernel/bpf/offload.c (ffff80001028a1e0)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051cd2c)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffff800010636b40)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06784)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08158)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4eda8)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf144)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf18)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd48)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b34)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e5c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (c04b985c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c06d9328)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (c07dc858)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f90c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20fc4)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5eeac)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c0dcaa3c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d24)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de6cb4)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e46fe4)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52efc)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (c0000000003355a0)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000665e84)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca1c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0cf0)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf25e0)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d44c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c000000000dd9cf0)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb410)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc69c)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e79638)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa24)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffe0001be33a)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe00038483e)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640e4)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784cf2)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007861c0)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bab3c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffe000815014)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe0008208e4)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082aa9c)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087f564)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a53c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811fa44b)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142efd1)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a1a)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902c59)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903b0d)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8194055e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819a60fe)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2104)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bff42)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a36e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258d3)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811ed19b)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141fa51)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513cfa)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bca89)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd93d)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa04e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fbbe)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e734)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cd32)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d712e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2693)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811f821b)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142b171)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151faaa)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81953c89)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954b3d)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819916ee)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1099e)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9a4)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a9c2)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a84dee)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90353)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff8120657a)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81442054)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In lib/rhashtable.c (ffffffff8153938f)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff8197540c)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819767e2)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4173)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b212)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27960)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35f67)
Location: include/linux/rhashtable.h:294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a9176a)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf4d)
Location: include/linux/rhashtable.h:294
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
</ul>

## Differences
