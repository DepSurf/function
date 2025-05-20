# Function: <code>__rhashtable_lookup</code>

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
In security/apparmor/apparmorfs.c (ffffffff813c5212)
Location: include/linux/rhashtable.h:560
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/netlink/af_netlink.c (ffffffff817e8788)
Location: include/linux/rhashtable.h:560
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5034)
Location: include/linux/rhashtable.h:560
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
In security/apparmor/apparmorfs.c (ffffffff813db5ff)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/netlink/af_netlink.c (ffffffff8180874b)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8186af97)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cba94)
Location: include/linux/rhashtable.h:600
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
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814020ab)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/sched/act_api.c (ffffffff81882702)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818875cb)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818eb737)
Location: include/linux/rhashtable.h:600
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950834)
Location: include/linux/rhashtable.h:600
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
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81432f26)
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/core/xdp.c (ffffffff818ba88b)
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d5d52)
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dac9b)
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819392f3)
Location: include/linux/rhashtable.h:616
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81944cca)
Location: include/linux/rhashtable.h:616
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9d2f)
Location: include/linux/rhashtable.h:616
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
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f12d9)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fbf8)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In net/core/xdp.c (ffffffff818e17bb)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/sched/cls_api.c (ffffffff818feff5)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8190757b)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968eab)
Location: include/linux/rhashtable.h:477
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81974e2a)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197feb4)
Location: include/linux/rhashtable.h:477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e084f)
Location: include/linux/rhashtable.h:477
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
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d57c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce0a)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff81930010)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8195f809)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8196882d)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfd86)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819de98a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c3a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f49f)
Location: include/linux/rhashtable.h:588
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
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814373cc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81496ada)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff81962270)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81963959)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199f2cd)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06916)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15a3a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20c8a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8612f)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct rhash_head *__rhashtable_lookup(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81228e10)
Location: include/linux/rhashtable.h:581
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81486661)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff814eecd5)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/core/xdp.c (ffffffff81a363af)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81a786b6)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6347)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06590)
Location: include/linux/rhashtable.h:581
Inline: False
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b13)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81643)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81228e10-ffffffff81228f3b: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81a35b20-ffffffff81a35bc8: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81b06590-ffffffff81b066be: __rhashtable_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct rhash_head *__rhashtable_lookup(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230a2a)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a3c44)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c14a)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/core/xdp.c (ffffffff81a37b99)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a819d2)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81b031bb)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14780)
Location: include/linux/rhashtable.h:581
Inline: False
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21093)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90e73)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81230bd0-ffffffff81230cb3: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81b14780-ffffffff81b148ae: __rhashtable_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct rhash_head *__rhashtable_lookup(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234bda)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff814a9c44)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81512ada)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1ed29)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6aad2)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee973)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b02580)
Location: include/linux/rhashtable.h:581
Inline: False
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ecc3)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80073)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81234d80-ffffffff81234e5b: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81b02580-ffffffff81b026a8: __rhashtable_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct rhash_head *__rhashtable_lookup(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126ecf6)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffff815020f4)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff815706da)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/core/xdp.c (ffffffff81ad2dc9)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b240d2)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81baed43)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc44f0)
Location: include/linux/rhashtable.h:581
Inline: False
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd20c3)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a795)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b923)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8126eeb0-ffffffff8126ef8b: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81bc44f0-ffffffff81bc4618: __rhashtable_lookup (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff812be5ac)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593719)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c553)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/core/xdp.c (ffffffff81c510e9)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac6f4)
Location: include/linux/rhashtable.h:581
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42096)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59570)
Location: include/linux/rhashtable.h:581
Inline: True
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6866d)
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd863a)
Location: include/linux/rhashtable.h:581
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
Location: include/linux/rhashtable.h:581
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81d59570-ffffffff81d5969d: __rhashtable_lookup.isra.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff8132124b)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d124)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In ipc/util.c (ffffffff8163c169)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec38)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/core/xdp.c (ffffffff81e05d99)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6a2f4)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0aed6)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f239b0)
Location: include/linux/rhashtable.h:589
Inline: True
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3370d)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa04a)
Location: include/linux/rhashtable.h:589
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
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81321470-ffffffff81321553: __rhashtable_lookup.constprop.0 (STB_LOCAL)
ffffffff81f239b0-ffffffff81f23add: __rhashtable_lookup.isra.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff813519af)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137df73)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In ipc/util.c (ffffffff81674701)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f76fc)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/core/xdp.c (ffffffff81e78ab4)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec62c4)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa16)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83500)
Location: include/linux/rhashtable.h:589
Inline: True
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92a8d)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a990)
Location: include/linux/rhashtable.h:589
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
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff820935cf)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_hash_lookup
```
**Symbols:**

```
ffffffff81f83500-ffffffff81f83668: __rhashtable_lookup.isra.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff81378e8f)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a71d3)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In ipc/util.c (ffffffff816b0ac1)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8173446f)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/core/xdp.c (ffffffff81f38984)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f89534)
Location: include/linux/rhashtable.h:589
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820310c6)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff82049bb0)
Location: include/linux/rhashtable.h:589
Inline: True
Direct callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d0f6)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d9960)
Location: include/linux/rhashtable.h:589
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
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169e7f)
Location: include/linux/rhashtable.h:589
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_hash_lookup
```
**Symbols:**

```
ffffffff82049bb0-ffffffff82049d18: __rhashtable_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a60c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffff80001051dbd0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffff80001058ccf4)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffff800010c06544)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffff800010c07ec0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4cdfc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf7b4)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1610)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6a0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffff800010d526a0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffff800010289bc8-ffff800010289d40: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
ffff800010d51c10-ffff800010d51d70: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct rhash_head *__rhashtable_lookup(struct rhashtable *ht, const void *key, const struct rhashtable_params params);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9734)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da06c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c073d9e4)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (c0d1f5f0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (c0d20da4)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dfc0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c0dcb190)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (c0ddb4e8)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6ae8)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c0e52a94)
Location: include/linux/rhashtable.h:588
Inline: True
```
**Symbols:**

```
c0d1fc60-c0d1fdb0: __rhashtable_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (c0000000003360bc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (c000000000666f9c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c0000000006fed20)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (c000000000cf0a00)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c000000000cf22a8)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4bbd8)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda544)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (c000000000def7a8)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe898)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c000000000e8acfc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
c000000000335290-c00000000033545c: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
c000000000e8a300-c000000000e8a4ac: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be632)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In ipc/util.c (ffffffe0003853e2)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffe0003dafde)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffe000784ae0)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffe000785f60)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9cda)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe00081548c)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffe000822bb2)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dbcc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a6cc)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffe00088a310-ffffffe00088a45a: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
ffffffe0001be0e4-ffffffe0001be234: __rhashtable_lookup.isra.0.constprop.0 (STB_LOCAL)
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
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142f9ac)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f0ba)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff81902240)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81903929)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193f13d)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a66b6)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819b50ca)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c031a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a257bf)
Location: include/linux/rhashtable.h:588
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
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142042c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fada)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff818bc070)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff818bd759)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f8c3d)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81960176)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819716fa)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d10a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e257f)
Location: include/linux/rhashtable.h:588
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
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bb4c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b15a)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff81953270)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff81954959)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819902cd)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10f56)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f96a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ad9a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9023f)
Location: include/linux/rhashtable.h:588
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
In kernel/bpf/offload.c (ffffffff8120644b)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442b66)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3052)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/core/xdp.c (ffffffff81974d7c)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (ffffffff81976614)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2bbd)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b8bb)
Location: include/linux/rhashtable.h:588
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2ae6a)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a363bf)
Location: include/linux/rhashtable.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d4b8)
Location: include/linux/rhashtable.h:588
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
<b>Arch</b>
<ul>
</ul>
