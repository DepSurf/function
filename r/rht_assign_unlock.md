# Function: <code>rht_assign_unlock</code>

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
In kernel/bpf/offload.c (ffffffff811f516b)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141d054)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e4c)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150db7e)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819308d1)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81962b00)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969dd7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfc37)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbc70)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9a05)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44477)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f6f2)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff81202163)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436ea4)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2cfc)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b9ce)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81962e3b)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81964004)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a0847)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a067c7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12ba0)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a217b2)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b067)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86382)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff812293dc)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In ipc/util.c (ffffffff81486a5d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcfec)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e05e)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/core/xdp.c (ffffffff81a3612d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a7934f)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af601d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01dfd)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b109ed)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7538d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8158d)
Location: include/linux/rhashtable.h:394
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
In kernel/bpf/offload.c (ffffffff81230f6c)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In ipc/util.c (ffffffff814a410d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a201)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aabee)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/core/xdp.c (ffffffff81a384fd)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a8215f)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e8d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fedd)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ece2)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b840fd)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90dcd)
Location: include/linux/rhashtable.h:394
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
In kernel/bpf/offload.c (ffffffff81235102)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In ipc/util.c (ffffffff814aa034)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520b0f)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b5d76)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81a1f334)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b247)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee784)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afdacd)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c968)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d7d)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ffd4)
Location: include/linux/rhashtable.h:394
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
In kernel/bpf/offload.c (ffffffff8126f23e)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In ipc/util.c (ffffffff815024f0)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ecaf)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c216)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81ad35d0)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b24873)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeb40)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfbdc)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfb58)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a324)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d2cc)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b880)
Location: include/linux/rhashtable.h:394
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
In kernel/bpf/offload.c (ffffffff812be0e4)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In ipc/util.c (ffffffff81593a7c)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d7c3)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In lib/rhashtable.c (ffffffff816eaad2)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81c50df6)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cac08e)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41a9a)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55f91)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68240)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd80b4)
Location: include/linux/rhashtable.h:394
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb6d6)
Location: include/linux/rhashtable.h:394
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaef5)
Location: include/linux/rhashtable.h:394
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
In kernel/bpf/offload.c (ffffffff813217c5)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d74a)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In ipc/util.c (ffffffff8163c66a)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d12ee)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In lib/rhashtable.c (ffffffff817dad66)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e064ba)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69c62)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a78c)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f206bd)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f332f3)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa9979)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae2d0)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea92)
Location: include/linux/rhashtable.h:401
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
In kernel/bpf/offload.c (ffffffff813513a9)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e670)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In ipc/util.c (ffffffff81674b5d)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a1fe)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819fdf)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81e78d94)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5bf6)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a2bc)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f801aa)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f926ca)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a2fb)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200ea3e)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa4c)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/handshake/request.c (ffffffff82092d80)
Location: include/linux/rhashtable.h:401
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
In kernel/bpf/offload.c (ffffffff81378809)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a78d0)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In ipc/util.c (ffffffff816b0f1d)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747cfe)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185f32f)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81f38c64)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88e56)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8203096c)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204682a)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206043a)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d929c)
Location: include/linux/rhashtable.h:401
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd9ce)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb7c)
Location: include/linux/rhashtable.h:401
Inline: True
```
```
In net/handshake/request.c (ffffffff82169630)
Location: include/linux/rhashtable.h:401
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
In kernel/bpf/offload.c (ffff80001028a450)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d5c0)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598ac4)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffff8000106370c8)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffff800010c06938)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08750)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4ef28)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf638)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc20c)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcec8)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44e3c)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51fb0)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (c04b9b1c)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d99c8)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749cf0)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (c07dcf08)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c0d1fab4)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d21944)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5f090)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcaf98)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd803c)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7cdc)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e470b8)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e530a0)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (c000000000335870)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666724)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070fa54)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (c0000000007dd140)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (c000000000cf0ef0)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2e64)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d660)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda2cc)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb4e0)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfceac)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e79710)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8abc0)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffe0001be4d6)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384e66)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e53a8)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004644d6)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffe000784dde)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078656c)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bac62)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815356)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe000820964)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c1ea)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f5e4)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a614)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff811fa783)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f484)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b2dc)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523fae)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81902e0b)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903fd4)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819406b7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6567)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2460)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0e42)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a6f7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25a12)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff811ed4d3)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141ff04)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bcfc)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151428e)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff818bcc3b)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bde04)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa1a7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81960027)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196ea90)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197dc32)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d74b7)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e27d2)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff811f8553)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b624)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149737c)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152003e)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff81953e3b)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81955004)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81991847)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10e07)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cd00)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b8c2)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a85177)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90492)
Location: include/linux/rhashtable.h:399
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
In kernel/bpf/offload.c (ffffffff812068f6)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814425cc)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af473)
Location: include/linux/rhashtable.h:399
Inline: True
```
```
In lib/rhashtable.c (ffffffff8153996d)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In net/core/xdp.c (ffffffff819755f4)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976ff3)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b4356)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b6d8)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27c4f)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36f59)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91a92)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d113)
Location: include/linux/rhashtable.h:399
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
