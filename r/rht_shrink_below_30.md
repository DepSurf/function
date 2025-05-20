# Function: <code>rht_shrink_below_30</code>

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
In lib/rhashtable.c (ffffffff8140093b)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8174e236)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
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
In lib/rhashtable.c (ffffffff814480e0)
Location: include/linux/rhashtable.h:273
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817ba3ea)
Location: include/linux/rhashtable.h:273
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
In lib/rhashtable.c (ffffffff81466d00)
Location: include/linux/rhashtable.h:290
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e9a68)
Location: include/linux/rhashtable.h:290
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a51d0)
Location: include/linux/rhashtable.h:290
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
In lib/rhashtable.c (ffffffff8146ba12)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81809938)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff8186b3e7)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbc7b)
Location: include/linux/rhashtable.h:304
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
In ipc/util.c (ffffffff813a6ffa)
Location: include/linux/rhashtable.h:304
Inline: True
```
```
In lib/rhashtable.c (ffffffff81497d02)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882979)
Location: include/linux/rhashtable.h:304
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81888841)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff818ebbc1)
Location: include/linux/rhashtable.h:304
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950a20)
Location: include/linux/rhashtable.h:304
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
In ipc/util.c (ffffffff813d682f)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In lib/rhashtable.c (ffffffff814cd25b)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818bae51)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d62d8)
Location: include/linux/rhashtable.h:313
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dc2e5)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81939210)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819423bb)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/ip6mr.c (ffffffff8199eab5)
Location: include/linux/rhashtable.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9f1b)
Location: include/linux/rhashtable.h:313
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
In kernel/bpf/offload.c (ffffffff811df6ff)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff813f0ebc)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In lib/rhashtable.c (ffffffff814e1ad1)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e1ee3)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901614)
Location: include/linux/rhashtable.h:179
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81908cb7)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81968ddd)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819721b8)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fceb)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d54aa)
Location: include/linux/rhashtable.h:179
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0a48)
Location: include/linux/rhashtable.h:179
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
In kernel/bpf/offload.c (ffffffff811f5070)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141cc82)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150dd5c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81930881)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819626f3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969dfc)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf909)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbf8)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9a29)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a4440c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f717)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff81202074)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81436ad2)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152bbac)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81962e60)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963c23)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a086c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06499)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12b28)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20a04)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7affc)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a863a7)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff812293fd)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff81486a7e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff8158f2f5)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81a3614e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a79370)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af603e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01e1e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b131a3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b753ae)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b815ae)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff81230f8d)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff814a412e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff815abebb)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81a3851e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a82180)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02eae)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fefe)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b215b3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b8411e)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90dee)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff81235120)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff814aa052)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff815b6a56)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81a1f352)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b265)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee7a2)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afdaeb)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f1d4)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d9b)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fff2)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff8126f25f)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff81502511)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In lib/rhashtable.c (ffffffff8161cfcf)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81ad35f1)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b24894)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeb61)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfbfa)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd25e3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c39b31)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d2ea)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b8a1)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff812be4a3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff81593d36)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ead75)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81c50e46)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81caded5)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41dea)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d56613)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68291)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd77fa)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddba37)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb216)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff81321838)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134da2f)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff8163c6dc)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff817db035)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81e0652c)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6b509)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ac69)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20e35)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33366)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa9219)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faec95)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbee5c)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff8135191c)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e6ac)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff81674e47)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8181a2a5)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81e78dcf)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec7554)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a7b9)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f801e5)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92706)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff82009bb9)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200ea79)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa87)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/handshake/request.c (ffffffff82092dbc)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff81378dfc)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a790c)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In ipc/util.c (ffffffff816b1207)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185f5f5)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81f38c9f)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8a894)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030e69)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82046865)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060476)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d8b59)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dda09)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eebb7)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/handshake/request.c (ffffffff8216966c)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffff80001028a494)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051ce50)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffff80001063734c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffff800010c06990)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08284)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ef74)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf268)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc29c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcf0c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44ecc)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51ffc)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (c04b9b70)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c06d94b0)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (c07dd180)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (c0d1fb88)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d21154)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5f104)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c0dcab74)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd8088)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de6ec8)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e47104)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e530f4)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (c0000000003358c4)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000665ff0)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (c0000000007dd4ac)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (c000000000cf0f3c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2758)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d6ac)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c000000000dd9e50)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb6e0)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc8b0)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e79910)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ac0c)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffe0001be50a)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe00038490e)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffe000464790)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffe000784e10)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786294)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bac94)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffe0008150c0)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe000820aca)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082abe6)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087f752)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a646)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff811fa694)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142f0b2)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152418c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81902e30)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903bf3)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819406dc)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6239)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23e8)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0094)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a68c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25a37)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff811ed3e4)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141fb32)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151446c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818bcc60)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bda23)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa1cc)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fcf9)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196ea18)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ce84)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d744c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e27f7)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff811f8464)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142b252)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152021c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff81953e60)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954c23)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199186c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ad9)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc88)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ab14)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a8510c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a904b7)
Location: include/linux/rhashtable.h:195
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
In kernel/bpf/offload.c (ffffffff812068a5)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8144216a)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In lib/rhashtable.c (ffffffff81539b9c)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff819755a7)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819768fe)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4303)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b358)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27be3)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a360cf)
Location: include/linux/rhashtable.h:195
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91a27)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d0c8)
Location: include/linux/rhashtable.h:195
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
</ul>

## Differences
