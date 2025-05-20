# Function: <code>__rhashtable_remove_fast_one</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9960)
Location: include/linux/rhashtable.h:942
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5102)
Location: include/linux/rhashtable.h:942
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
In net/netlink/af_netlink.c (ffffffff8180964b)
Location: include/linux/rhashtable.h:1008
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff8186b21c)
Location: include/linux/rhashtable.h:1008
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb64)
Location: include/linux/rhashtable.h:1008
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
In ipc/util.c (ffffffff813a6f35)
Location: include/linux/rhashtable.h:1010
Inline: True
```
```
In net/sched/act_api.c (ffffffff818828b4)
Location: include/linux/rhashtable.h:1010
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8188859c)
Location: include/linux/rhashtable.h:1010
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/ipmr.c (ffffffff818eb9ca)
Location: include/linux/rhashtable.h:1010
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950904)
Location: include/linux/rhashtable.h:1010
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
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818bad3c)
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d620f)
Location: include/linux/rhashtable.h:1021
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dbfbe)
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff8193912e)
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8194219f)
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv6/ip6mr.c (ffffffff8199e8f2)
Location: include/linux/rhashtable.h:1021
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e06)
Location: include/linux/rhashtable.h:1021
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
In kernel/bpf/offload.c (ffffffff811df40a)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff813f0e02)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In net/core/xdp.c (ffffffff818e1dd9)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff81901552)
Location: include/linux/rhashtable.h:889
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190898e)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff81968cfe)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81971f9f)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fbde)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5294)
Location: include/linux/rhashtable.h:889
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0931)
Location: include/linux/rhashtable.h:889
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
In kernel/bpf/offload.c (ffffffff811f4ded)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141cb76)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff8193074c)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819625de)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969c58)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf79a)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db8de)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98ac)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a440b5)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f585)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffff81201dfd)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814369c6)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff81962c5e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963b0e)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a06c8)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0632a)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1280e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2088c)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7aca5)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86215)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __rhashtable_remove_fast_one(struct rhashtable *ht, struct bucket_table *tbl, struct rhash_head *obj, const struct rhashtable_params params, bool rhlist);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812291e0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff81486850)
Location: include/linux/rhashtable.h:986
Inline: False
```
```
In net/core/xdp.c (ffffffff81a35f20)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a79170)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e10)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81b01c70)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12fa0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b75200)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81380)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff812291e0-ffffffff81229456: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81486850-ffffffff81486ad3: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a35f20-ffffffff81a361a3: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a79170-ffffffff81a793c5: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81af5e10-ffffffff81af6093: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b01c70-ffffffff81b01e6f: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b12fa0-ffffffff81b131fc: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81b75200-ffffffff81b753ff: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b81380-ffffffff81b81603: __rhashtable_remove_fast_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __rhashtable_remove_fast_one(struct rhashtable *ht, struct bucket_table *tbl, struct rhash_head *obj, const struct rhashtable_params params, bool rhlist);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230d70)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a3f00)
Location: include/linux/rhashtable.h:986
Inline: False
```
```
In net/core/xdp.c (ffffffff81a382f0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a81f80)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02c80)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81b0fd50)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b213b0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b83f70)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90bc0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81230d70-ffffffff81230fe6: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff814a3f00-ffffffff814a4183: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a382f0-ffffffff81a38573: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a81f80-ffffffff81a821d5: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b02c80-ffffffff81b02f03: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b0fd50-ffffffff81b0ff4f: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b213b0-ffffffff81b2160c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81b83f70-ffffffff81b8416f: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b90bc0-ffffffff81b90e43: __rhashtable_remove_fast_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __rhashtable_remove_fast_one(struct rhashtable *ht, struct bucket_table *tbl, struct rhash_head *obj, const struct rhashtable_params params, bool rhlist);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234f10)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a9e30)
Location: include/linux/rhashtable.h:986
Inline: False
```
```
In net/core/xdp.c (ffffffff81a1f130)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (ffffffff81a6b070)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee580)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81afd940)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0efc0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b72bf0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fdd0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81234f10-ffffffff81235175: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff814a9e30-ffffffff814aa0a7: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a1f130-ffffffff81a1f3a7: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81a6b070-ffffffff81a6b2ba: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81aee580-ffffffff81aee7f7: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81afd940-ffffffff81afdb38: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b0efc0-ffffffff81b0f229: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81b72bf0-ffffffff81b72de8: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81b7fdd0-ffffffff81b80047: __rhashtable_remove_fast_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __rhashtable_remove_fast_one(struct rhashtable *ht, struct bucket_table *tbl, struct rhash_head *obj, const struct rhashtable_params params, bool rhlist);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:986
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff8126f040-ffffffff8126f2b8: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81cb967c-ffffffff81cb9690: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff815022e0-ffffffff81502566: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81cd28a9-ffffffff81cd28bd: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81ad33c0-ffffffff81ad3646: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d377f0-ffffffff81d37804: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81b24690-ffffffff81b248e9: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d394e9-ffffffff81d394fd: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81bae930-ffffffff81baebb6: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d3daff-ffffffff81d3db13: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81bbfa40-ffffffff81bbfc4b: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d3ea36-ffffffff81d3ea4a: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81bd23c0-ffffffff81bd263c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81d3ed90-ffffffff81d3eda4: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81c39900-ffffffff81c39b86: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d41281-ffffffff81d41295: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81c3d130-ffffffff81c3d33b: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d4130c-ffffffff81d41320: __rhashtable_remove_fast_one.cold (STB_LOCAL)
ffffffff81c4b670-ffffffff81c4b8f6: __rhashtable_remove_fast_one (STB_LOCAL)
ffffffff81d4186e-ffffffff81d41882: __rhashtable_remove_fast_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:986
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff812be2f0-ffffffff812be569: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81e6aaa0-ffffffff81e6aab4: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81593b80-ffffffff81593dff: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81e859e8-ffffffff81e859fc: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81c50c90-ffffffff81c50f1b: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f0413a-ffffffff81f0414e: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81cadcd0-ffffffff81cadfa5: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f05c72-ffffffff81f05c87: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81d41be0-ffffffff81d41ebf: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff81f0a3f1-ffffffff81f0a405: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff81d56410-ffffffff81d566e3: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f0b3e4-ffffffff81f0b3f9: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81d680e0-ffffffff81d6835e: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f0b6d3-ffffffff81f0b6e7: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81dd75f0-ffffffff81dd78cf: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff81f0dbca-ffffffff81f0dbde: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff81ddb7c0-ffffffff81ddbb07: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f0dc42-ffffffff81f0dc57: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81deb060-ffffffff81deb2df: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff81f0e1d5-ffffffff81f0e1e9: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81321640-ffffffff81321894: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82061b35-ffffffff82061b49: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff8134d830-ffffffff8134da8b: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82061e90-ffffffff82061ea4: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff8163c4e0-ffffffff8163c73e: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82072bf6-ffffffff82072c0a: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81e06330-ffffffff81e065a1: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820ac827-ffffffff820ac83b: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81e6b2c0-ffffffff81e6b56b: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820ad9ca-ffffffff820ad9de: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f0aa20-ffffffff81f0acde: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff820b1cba-ffffffff820b1cce: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff81f20bf0-ffffffff81f20e97: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820b2cbc-ffffffff820b2cd0: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f33170-ffffffff81f333d3: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820b2f49-ffffffff820b2f5d: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81fa8fd0-ffffffff81fa928e: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff820b4fe9-ffffffff820b4ffd: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff81fae9e0-ffffffff81faecf7: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820b50ca-ffffffff820b50de: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81fbec60-ffffffff81fbeebe: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820b5393-ffffffff820b53a7: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/handshake/request.c:handshake_req_destroy
```
**Symbols:**

```
ffffffff813516c0-ffffffff8135196c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820e11b6-ffffffff820e11ca: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff8137e450-ffffffff8137e6fc: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820e162a-ffffffff820e163e: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81674bf0-ffffffff81674e9a: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff820f284d-ffffffff820f2861: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81e78bc0-ffffffff81e78e2e: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff8212debc-ffffffff8212ded0: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81ec72b0-ffffffff81ec75ae: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff8212ebb5-ffffffff8212ebc9: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f6a550-ffffffff81f6a818: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff82132ef2-ffffffff82132f06: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff81f7ff80-ffffffff81f80238: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82133e4c-ffffffff82133e60: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f924f0-ffffffff81f9275d: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff8213414d-ffffffff82134161: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff82009950-ffffffff82009c18: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff82135ec1-ffffffff82135ed5: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff8200e7a0-ffffffff8200eacc: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82135f7a-ffffffff82135f8e: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff8201f830-ffffffff8201fada: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82136273-ffffffff82136287: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff82092b60-ffffffff82092e0c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82138507-ffffffff8213851b: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/handshake/request.c (0)
Location: include/linux/rhashtable.h:995
Inline: True
Direct callers:
  - net/handshake/request.c:handshake_req_destroy
```
**Symbols:**

```
ffffffff81378ba0-ffffffff81378e4c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff821bda1d-ffffffff821bda31: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff813a76b0-ffffffff813a795c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff821be08d-ffffffff821be0a1: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff816b0fb0-ffffffff816b125a: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff821cfafd-ffffffff821cfb11: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f38a90-ffffffff81f38cfe: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff8220fc48-ffffffff8220fc5c: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff81f8a5e0-ffffffff81f8a8ee: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82210961-ffffffff82210975: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff82030c00-ffffffff82030ec8: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff822148d3-ffffffff822148e7: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff82046600-ffffffff820468b8: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82215858-ffffffff8221586c: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff82060260-ffffffff820604cd: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82215d53-ffffffff82215d67: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff820d88f0-ffffffff820d8bb8: __rhashtable_remove_fast_one.isra.0 (STB_LOCAL)
ffffffff82217af6-ffffffff82217b0a: __rhashtable_remove_fast_one.isra.0.cold (STB_LOCAL)
ffffffff820dd730-ffffffff820dda5c: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82217baf-ffffffff82217bc3: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff820ee960-ffffffff820eec0a: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff82217e43-ffffffff82217e57: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
ffffffff82169410-ffffffff821696bc: __rhashtable_remove_fast_one.constprop.0 (STB_LOCAL)
ffffffff8221a3c0-ffffffff8221a3d4: __rhashtable_remove_fast_one.constprop.0.cold (STB_LOCAL)
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
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051ccb8)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffff800010c06760)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c080d8)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ed88)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf118)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbe90)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd28)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44a40)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51de8)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (c04b982c)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c06d92f8)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (c0d1f8dc)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d20f94)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5ee7c)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c0dcaa0c)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7cf4)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de6c84)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e46fb4)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52ecc)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (c000000000335510)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000665e00)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (c000000000cf0cc0)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2550)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d420)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (c000000000dd9cb0)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb380)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc670)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e79500)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a9a0)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffe0001be2a0)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe0003847ae)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffe000784cc8)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786126)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007bab16)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffe000814fde)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe0008207fe)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082aa74)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3c0)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4ac)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffff811fa41d)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142efa6)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff81902c2e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903ade)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81940538)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff819a60ca)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b20ce)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bff1c)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a335)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258a5)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffff811ed16d)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8141fa26)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff818bca5e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd90e)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa028)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fb8a)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e6fe)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cd0c)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d70f5)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2665)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffff811f81ed)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8142b146)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff81953c5e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954b0e)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819916c8)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1096a)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c96e)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a99c)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a84db5)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90325)
Location: include/linux/rhashtable.h:993
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
In kernel/bpf/offload.c (ffffffff8120654c)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff8144202b)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/core/xdp.c (ffffffff819753e4)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819767b3)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b414d)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b1e0)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2792a)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a35f41)
Location: include/linux/rhashtable.h:993
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91731)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf24)
Location: include/linux/rhashtable.h:993
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
