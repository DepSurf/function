# Function: <code>rht_lock</code>

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
In kernel/bpf/offload.c (ffffffff811f4e37)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cf6e)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d90)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d5fb)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81930798)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819629c1)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969c96)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa95)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db92c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98ed)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44106)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5cb)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffff81201e47)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436dbe)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c40)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b44b)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81962ca1)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963eb9)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a0706)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06625)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1285c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21602)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7acf6)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8625b)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff8122925b)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff814868c8)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf27)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e9d7)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a35f98)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a791e3)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e88)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01cc0)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108de)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b75250)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b813f8)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff81230deb)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff814a3f78)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a137)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab537)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In net/core/xdp.c (ffffffff81a38368)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81ff3)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02cf8)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fda0)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebce)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fc0)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90c38)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff81234f8e)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff814a9eac)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a46)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b6399)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f1ac)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b0e2)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5fc)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd992)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c859)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c42)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fe4c)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff8126f0be)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff8150235c)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebe6)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c8c9)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad343c)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b24702)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9ac)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa92)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa49)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a192)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d182)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b6ec)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff812be007)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff815939a7)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6d9)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea0d3)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c50ce7)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabfdb)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418b8)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55df5)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68133)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7eef)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb50a)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae0d)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff81321695)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d548)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff8163c538)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d118a)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da2f1)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e06388)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69bab)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6d2)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20525)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331c3)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa98e1)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae10a)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe9ed)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff81351236)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e4e9)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff816749f1)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a09a)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819673)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78c0b)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b45)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a202)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80021)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92543)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a261)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e8b5)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f8c3)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/handshake/request.c (ffffffff82092bf9)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff81378696)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7749)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In ipc/util.c (ffffffff816b0db1)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747b9a)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e9c3)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38adb)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88da5)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820308b2)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820466a1)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820602b3)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9202)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd845)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee9f3)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/handshake/request.c (ffffffff821694a9)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffff80001028a1f4)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d480)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff80001059897c)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffff800010636b48)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06798)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08620)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4edbc)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf46c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf2c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd5c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b48)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e70)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (c04b9878)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d9864)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749bb0)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (c07dc870)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1f928)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2170c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5eec8)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcade0)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d40)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7a4c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47000)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f18)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (c0000000003355b8)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c0000000006665f0)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f900)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca38)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0d08)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c64)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d464)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda0e0)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb428)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd1c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79650)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa3c)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffe0001be2a8)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384d74)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52f8)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640f8)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784cca)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078646c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bab16)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe00081524a)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082083c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0fe)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f402)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4b4)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffff811fa467)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f39e)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b220)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a2b)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902c71)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e89)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81940576)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63c5)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b211c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c92)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a386)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258eb)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffff811ed1b7)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fe1e)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc40)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513d0b)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bcaa1)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcb9)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa066)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe85)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e74c)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da82)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7146)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26ab)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffff811f8237)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b53e)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814972c0)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fabb)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81953ca1)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954eb9)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81991706)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c65)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9bc)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b712)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e06)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9036b)
Location: include/linux/rhashtable.h:327
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
In kernel/bpf/offload.c (ffffffff81206596)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814424d0)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af398)
Location: include/linux/rhashtable.h:327
Inline: True
```
```
In lib/rhashtable.c (ffffffff815393a0)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81975424)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976e94)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b418b)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b542)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27978)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d5a)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91782)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf65)
Location: include/linux/rhashtable.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
