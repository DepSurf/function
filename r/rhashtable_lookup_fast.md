# Function: <code>rhashtable_lookup_fast</code>

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
In lib/rhashtable.c (ffffffff81400b97)
Location: include/linux/rhashtable.h:528
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174be2d)
Location: include/linux/rhashtable.h:528
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813ae405)
Location: include/linux/rhashtable.h:529
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In lib/rhashtable.c (ffffffff8144831b)
Location: include/linux/rhashtable.h:529
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff817b8cf0)
Location: include/linux/rhashtable.h:529
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813c5212)
Location: include/linux/rhashtable.h:629
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/netlink/af_netlink.c (ffffffff817e8788)
Location: include/linux/rhashtable.h:629
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5034)
Location: include/linux/rhashtable.h:629
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In security/apparmor/apparmorfs.c (ffffffff813db57f)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/netlink/af_netlink.c (ffffffff8180874b)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cba94)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In ipc/util.c (ffffffff813a78ff)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8140202b)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/sched/act_api.c (ffffffff81882702)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818875cb)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950834)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In ipc/util.c (ffffffff813d6ce2)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81432f26)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/core/xdp.c (ffffffff818baca4)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d5d52)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dac9b)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9d2f)
Location: include/linux/rhashtable.h:685
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811df316)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f12d9)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fbf8)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/core/xdp.c (ffffffff818e1d39)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff818feff5)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8190757b)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819806f4)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e084f)
Location: include/linux/rhashtable.h:553
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff811f4cf6)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d57c)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce0a)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff81930c06)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8195f809)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8196882d)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea411)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f49f)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81201d06)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814373cc)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81496ada)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff81962bab)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81963959)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199f2cd)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21461)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8612f)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81229494)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81486653)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff814eecd5)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a786b6)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12de3)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81643)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff81231024)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c44)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c14a)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a819d2)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b211e3)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90e73)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff812351b4)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c44)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81512ada)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6aad2)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ee03)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80073)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *rhashtable_lookup_fast(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126f2f6)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff815020f4)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff815706da)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b240d2)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2203)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a795)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
Direct callers:
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b923)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81c39560-ffffffff81c396b4: rhashtable_lookup_fast (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff812be5a7)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593714)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c54e)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cac6ef)
Location: include/linux/rhashtable.h:657
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69298)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd863a)
Location: include/linux/rhashtable.h:657
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb30b)
Location: include/linux/rhashtable.h:657
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
In kernel/bpf/offload.c (ffffffff813218e6)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8163c164)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec33)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6a2ef)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34578)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa04a)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeefb)
Location: include/linux/rhashtable.h:665
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
In kernel/bpf/offload.c (ffffffff813519aa)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff816746f5)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f76f7)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec62bf)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f94198)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a987)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb1d)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff820935b9)
Location: include/linux/rhashtable.h:665
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
In kernel/bpf/offload.c (ffffffff81378e8a)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff816b0ab5)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8173446a)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8952f)
Location: include/linux/rhashtable.h:665
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061553)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d9957)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eec4d)
Location: include/linux/rhashtable.h:665
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169e69)
Location: include/linux/rhashtable.h:665
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
In kernel/bpf/offload.c (ffff80001028a118)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dbd0)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffff80001058ccf4)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffff800010c066c0)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffff800010c07ec0)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4cdfc)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc8d8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51da8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (c04b96e0)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da020)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c073d9b4)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (c0d1f794)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c0d20d60)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5df88)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (c0de7878)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c0e52a24)
Location: include/linux/rhashtable.h:664
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
**Symbols:**

```
c0e52a24-c0e52ba4: rhashtable_lookup_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (c0000000003354b0)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000666f9c)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c0000000006fed20)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (c000000000cf0bfc)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c000000000cf22a8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4bbd8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcb2c)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a954)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffe0001be278)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe0003853e2)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffe0003dafde)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffe000784c30)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffe000785f60)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9cda)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082bfa8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a488)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811fa326)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142f9ac)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f0ba)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff81902b7b)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81903929)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193f13d)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0af1)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a257bf)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811ed076)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142042c)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fada)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff818bc9ab)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff818bd759)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f8c3d)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d8e1)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e257f)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff811f80f6)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bb4c)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b15a)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff81953bab)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81954959)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819902cd)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b571)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9023f)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
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
In kernel/bpf/offload.c (ffffffff81206446)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442b61)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814a304d)
Location: include/linux/rhashtable.h:664
Inline: True
```
```
In net/core/xdp.c (ffffffff81975a93)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (ffffffff8197660f)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2bb8)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36ba1)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d4b3)
Location: include/linux/rhashtable.h:664
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
