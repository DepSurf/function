# Function: <code>rhashtable_remove_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174de26)
Location: include/linux/rhashtable.h:792
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b9fd9)
Location: include/linux/rhashtable.h:793
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff817e995d)
Location: include/linux/rhashtable.h:1058
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a50fd)
Location: include/linux/rhashtable.h:1058
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In net/netlink/af_netlink.c (ffffffff81809647)
Location: include/linux/rhashtable.h:1124
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb5f)
Location: include/linux/rhashtable.h:1124
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
In ipc/util.c (ffffffff813a6f2d)
Location: include/linux/rhashtable.h:1126
Inline: True
```
```
In net/sched/act_api.c (ffffffff818828b1)
Location: include/linux/rhashtable.h:1126
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81888598)
Location: include/linux/rhashtable.h:1126
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv6/seg6_hmac.c (ffffffff819508ff)
Location: include/linux/rhashtable.h:1126
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
In ipc/util.c (ffffffff813d6772)
Location: include/linux/rhashtable.h:1137
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818bad35)
Location: include/linux/rhashtable.h:1137
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d620b)
Location: include/linux/rhashtable.h:1137
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dbfba)
Location: include/linux/rhashtable.h:1137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81939122)
Location: include/linux/rhashtable.h:1137
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e02)
Location: include/linux/rhashtable.h:1137
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
In kernel/bpf/offload.c (ffffffff811df403)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff813f0e02)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818e1dd2)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901535)
Location: include/linux/rhashtable.h:1005
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190898a)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81968cf2)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fbde)
Location: include/linux/rhashtable.h:1005
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e092d)
Location: include/linux/rhashtable.h:1005
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
In kernel/bpf/offload.c (ffffffff811f4de0)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141cb68)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff81930aa1)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff819625c5)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969c54)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf78f)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98a5)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f57a)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff81201df0)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814369b8)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff81962c55)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963af5)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a06c4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0631f)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2087f)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8620a)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff81229501)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81486af9)
Location: include/linux/rhashtable.h:1108
Inline: True
```
```
In net/core/xdp.c (ffffffff81a361d7)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a79f43)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6136)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1327d)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b816ec)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81231051)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a41af)
Location: include/linux/rhashtable.h:1108
Inline: True
```
```
In net/core/xdp.c (ffffffff81a385ac)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a82da4)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02fab)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21691)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90ef8)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff812351e1)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814aa0cf)
Location: include/linux/rhashtable.h:1108
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1f3dc)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a6be74)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee89b)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f2b1)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b800f4)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff8126f323)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8150258f)
Location: include/linux/rhashtable.h:1108
Inline: True
```
```
In net/core/xdp.c (ffffffff81ad367c)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81b254dd)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81baec6d)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd26c1)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c39ec6)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b9a4)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff812be650)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81593e15)
Location: include/linux/rhashtable.h:1108
Inline: True
```
```
In net/core/xdp.c (ffffffff81c50fb6)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81cae006)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41fb2)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d683d8)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd7bab)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb383)
Location: include/linux/rhashtable.h:1108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81321918)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8163c765)
Location: include/linux/rhashtable.h:1118
Inline: True
```
```
In net/core/xdp.c (ffffffff81e06656)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81e6b5d6)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ade2)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33468)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81fa958b)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef73)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81351a9a)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81674ec5)
Location: include/linux/rhashtable.h:1118
Inline: True
```
```
In net/core/xdp.c (ffffffff81e78ed6)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81ec7616)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a922)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f927e8)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff82009f0b)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fbc5)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (ffffffff82092e4c)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_destroy
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
In kernel/bpf/offload.c (ffffffff81378f7a)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff816b1285)
Location: include/linux/rhashtable.h:1118
Inline: True
```
```
In net/core/xdp.c (ffffffff81f38da6)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81f8a956)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff82030fd2)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060558)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d8eab)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eecf5)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (ffffffff821696fc)
Location: include/linux/rhashtable.h:1118
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_destroy
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
In kernel/bpf/offload.c (ffff80001028a144)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051cc9c)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffff800010c0674c)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c080b4)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ed78)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf104)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd0c)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51dcc)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (c04b97e4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c06d92b0)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (c0d1f894)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20f40)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5ee30)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c0dca9c0)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (c0de6c34)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c0e52e80)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (c0000000003354f4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000665df0)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (c000000000cf0ca4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2530)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d410)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c000000000dd9c8c)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc654)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a98c)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffe0001be29c)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe0003847aa)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffe000784cc4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078611a)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bab12)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffe000814fda)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082aa68)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4a8)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff811fa410)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142ef98)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff81902c25)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903ac5)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81940534)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819a60bf)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bff0f)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2589a)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff811ed160)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141fa18)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff818bca55)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd8f5)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa024)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fb7f)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ccff)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e265a)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff811f81e0)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142b138)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff81953c55)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954af5)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819916c4)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1095f)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a98f)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9031a)
Location: include/linux/rhashtable.h:1115
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
In kernel/bpf/offload.c (ffffffff8120653a)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81442019)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/core/xdp.c (ffffffff81975b85)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976795)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4144)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b1cb)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35f2f)
Location: include/linux/rhashtable.h:1115
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf15)
Location: include/linux/rhashtable.h:1115
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
</ul>

## Differences
