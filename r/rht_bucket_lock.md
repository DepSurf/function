# Function: <code>rht_bucket_lock</code>

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
In lib/rhashtable.c (0)
Location: include/linux/rhashtable.h:318
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:318
Inline: True
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
In security/apparmor/policy_unpack.c (ffffffff813bc09e)
Location: include/linux/rhashtable.h:318
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814482f9)
Location: include/linux/rhashtable.h:318
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b9ff9)
Location: include/linux/rhashtable.h:318
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
In security/apparmor/policy_unpack.c (ffffffff813d3565)
Location: include/linux/rhashtable.h:335
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81466880)
Location: include/linux/rhashtable.h:335
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e997b)
Location: include/linux/rhashtable.h:335
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5124)
Location: include/linux/rhashtable.h:335
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
In security/apparmor/policy_unpack.c (ffffffff813e666e)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146c0ff)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8180966b)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186b268)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb83)
Location: include/linux/rhashtable.h:348
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
In ipc/util.c (ffffffff813a725d)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d852)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81498402)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882b1e)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818885bc)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818eba1b)
Location: include/linux/rhashtable.h:348
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950928)
Location: include/linux/rhashtable.h:348
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
In ipc/util.c (ffffffff813d67a3)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef8c)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cd5f6)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818bad6a)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d655e)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818dbfe4)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81939169)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819421d7)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199e92a)
Location: include/linux/rhashtable.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e33)
Location: include/linux/rhashtable.h:357
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
In kernel/bpf/offload.c (ffffffff811df435)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0e2c)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be9b)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e17f5)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/xdp.c (ffffffff818e1e02)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901947)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819089ad)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d36)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971fd0)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fc07)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d52c5)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0954)
Location: include/linux/rhashtable.h:223
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
