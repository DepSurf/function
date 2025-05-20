# Function: <code>__rhashtable_remove_fast</code>

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
In net/netlink/af_netlink.c (ffffffff8174de2a)
Location: include/linux/rhashtable.h:745
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
In net/netlink/af_netlink.c (ffffffff817b9fdd)
Location: include/linux/rhashtable.h:746
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
Location: include/linux/rhashtable.h:1017
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a50fd)
Location: include/linux/rhashtable.h:1017
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
Location: include/linux/rhashtable.h:1083
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff8186b21c)
Location: include/linux/rhashtable.h:1083
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb5f)
Location: include/linux/rhashtable.h:1083
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
Location: include/linux/rhashtable.h:1085
Inline: True
```
```
In net/sched/act_api.c (ffffffff818828b1)
Location: include/linux/rhashtable.h:1085
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81888598)
Location: include/linux/rhashtable.h:1085
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff818eb9ca)
Location: include/linux/rhashtable.h:1085
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819508ff)
Location: include/linux/rhashtable.h:1085
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
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818bad35)
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d620b)
Location: include/linux/rhashtable.h:1096
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dbfba)
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81939122)
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81942198)
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/ip6mr.c (ffffffff8199e8eb)
Location: include/linux/rhashtable.h:1096
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e02)
Location: include/linux/rhashtable.h:1096
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
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff813f0e02)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818e1dd2)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901535)
Location: include/linux/rhashtable.h:964
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190898a)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81968cf2)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971f98)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fbde)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d528d)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e092d)
Location: include/linux/rhashtable.h:964
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4de0)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141cb68)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff81930730)
Location: include/linux/rhashtable.h:1074
Inline: True
Direct callers:
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff819625c5)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969c54)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf78f)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db8d3)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98a5)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440ae)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f57a)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81930730-ffffffff819308f6: __rhashtable_remove_fast.constprop.0 (STB_LOCAL)
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814369b8)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff81962c55)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963af5)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a06c4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0631f)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12803)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2087f)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ac9e)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8620a)
Location: include/linux/rhashtable.h:1074
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
In kernel/bpf/offload.c (ffffffff8122952e)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81486b31)
Location: include/linux/rhashtable.h:1067
Inline: True
```
```
In net/core/xdp.c (ffffffff81a36211)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a79f4f)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6157)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81b03e1c)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b132a6)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b754f3)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81723)
Location: include/linux/rhashtable.h:1067
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
In kernel/bpf/offload.c (ffffffff81231088)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a41e1)
Location: include/linux/rhashtable.h:1067
Inline: True
```
```
In net/core/xdp.c (ffffffff81a385e2)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a82db0)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02fcc)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81b11f8c)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b216ba)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b84263)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90f2f)
Location: include/linux/rhashtable.h:1067
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
In kernel/bpf/offload.c (ffffffff81235218)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814aa101)
Location: include/linux/rhashtable.h:1067
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1f412)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a6be80)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee8bc)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81aff6ce)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f2da)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b72ef5)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8012b)
Location: include/linux/rhashtable.h:1067
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
In kernel/bpf/offload.c (ffffffff8126f35a)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff815025c2)
Location: include/linux/rhashtable.h:1067
Inline: True
```
```
In net/core/xdp.c (ffffffff81ad36b2)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81b254ed)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81baec8e)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81bc1465)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd26ea)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c39ef2)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d43e)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b9db)
Location: include/linux/rhashtable.h:1067
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
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81593e15)
Location: include/linux/rhashtable.h:1067
Inline: True
```
```
In net/core/xdp.c (ffffffff81c50fb6)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81cae006)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41fb2)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81d569ae)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d683d8)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd7bab)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddbdd7)
Location: include/linux/rhashtable.h:1067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb383)
Location: include/linux/rhashtable.h:1067
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
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134dbb8)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In ipc/util.c (ffffffff8163c765)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In net/core/xdp.c (ffffffff81e06656)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81e6b5d6)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ade2)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81f2127e)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33468)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff81fa958b)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (ffffffff81faefe7)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbef73)
Location: include/linux/rhashtable.h:1077
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
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137ebd7)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In ipc/util.c (ffffffff81674ec5)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In net/core/xdp.c (ffffffff81e78ed6)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81ec7616)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a922)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81f8051d)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f927e8)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff82009f0b)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (ffffffff8200edb8)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fbc5)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (ffffffff82092e4c)
Location: include/linux/rhashtable.h:1077
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
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7e37)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In ipc/util.c (ffffffff816b1285)
Location: include/linux/rhashtable.h:1077
Inline: True
```
```
In net/core/xdp.c (ffffffff81f38da6)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81f8a956)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff82030fd2)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff82046b9d)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060558)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d8eab)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (ffffffff820ddd48)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eecf5)
Location: include/linux/rhashtable.h:1077
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (ffffffff821696fc)
Location: include/linux/rhashtable.h:1077
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051cc9c)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffff800010c0674c)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c080b4)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ed78)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf104)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbe84)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd0c)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44a34)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51dcc)
Location: include/linux/rhashtable.h:1074
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
In kernel/bpf/offload.c (c04b97f4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c06d92c0)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (c0d1f8a4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20f50)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5ee44)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c0dca9d0)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7cc8)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de6c44)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e46f88)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52e90)
Location: include/linux/rhashtable.h:1074
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000665df0)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (c000000000cf0ca4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2530)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d410)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c000000000dd9c8c)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb370)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc654)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e794f0)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a98c)
Location: include/linux/rhashtable.h:1074
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe0003847aa)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffe000784cc4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078611a)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bab12)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffe000814fda)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe0008207fc)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082aa68)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3be)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4a8)
Location: include/linux/rhashtable.h:1074
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142ef98)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff81902c25)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903ac5)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81940534)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819a60bf)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b20c3)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bff0f)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a32e)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2589a)
Location: include/linux/rhashtable.h:1074
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141fa18)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff818bca55)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd8f5)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa024)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fb7f)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e6f3)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ccff)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d70ee)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e265a)
Location: include/linux/rhashtable.h:1074
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
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142b138)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff81953c55)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954af5)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819916c4)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1095f)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c963)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a98f)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a84dae)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9031a)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8120653a)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81442019)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/core/xdp.c (ffffffff819753d1)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (ffffffff81976795)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4144)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b1cb)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2791a)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35f2f)
Location: include/linux/rhashtable.h:1074
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91725)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf15)
Location: include/linux/rhashtable.h:1074
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81975710-ffffffff81975947: __rhashtable_remove_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
