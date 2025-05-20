# Function: <code>jhash2</code>

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
In kernel/futex.c (ffffffff810ffd25)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In mm/hugetlb.c (ffffffff811dd1af)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff811e605d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In lib/rhashtable.c (ffffffff81400660)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff817116f9)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow_dissector.c:flow_hash_from_keys
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:skb_get_hash_perturb
```
```
In net/core/flow.c (ffffffff817347e2)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8174b841)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1e2b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff817e3537)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/futex.c (ffffffff81106e96)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/stackmap.c (ffffffff8118844b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff811fb492)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff81204ee7)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff81447df0)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff8177a686)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/flow.c (ffffffff817a08d8)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817b8821)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181ed5a)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff81851c39)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/futex.c (ffffffff8110e656)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/stackmap.c (ffffffff811972fb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8120bf92)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff8121516f)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff81466760)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff817a7c6e)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/flow.c (ffffffff817cf518)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817e82d1)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818505dd)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff818839f9)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5045)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash2(const u32 *k, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fee6)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/stackmap.c (ffffffff8119ef41)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff81217644)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff81220530)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146bfc0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff817c6285)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/flow.c (ffffffff817ee8b9)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81807ffd)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff8186afac)
Location: include/linux/jhash.h:116
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
In net/xfrm/xfrm_policy.c (ffffffff8187451f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff818a9cb0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbaa5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8146ac30-ffffffff8146ad08: jhash2 (STB_LOCAL)
ffffffff81806440-ffffffff81806518: jhash2 (STB_LOCAL)
ffffffff81868080-ffffffff81868158: jhash2 (STB_LOCAL)
ffffffff818cbe0c-ffffffff818cbedd: jhash2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash2(const u32 *k, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b1e6)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/stackmap.c (ffffffff811b1ee1)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff812322f4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff8123b770)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In ipc/util.c (ffffffff813a6b60)
Location: include/linux/jhash.h:116
Inline: True
Direct callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff814982c0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff8183fe85)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/sched/act_api.c (ffffffff81882706)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
Direct callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818869ed)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ipmr.c (ffffffff818eb74c)
Location: include/linux/jhash.h:116
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
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4a89)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff8192c6b0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950845)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff813a6b60-ffffffff813a6c38: jhash2 (STB_LOCAL)
ffffffff81496f10-ffffffff81496fe8: jhash2 (STB_LOCAL)
ffffffff81881600-ffffffff818816d8: jhash2 (STB_LOCAL)
ffffffff81885170-ffffffff81885248: jhash2 (STB_LOCAL)
ffffffff818e80f0-ffffffff818e81c8: jhash2 (STB_LOCAL)
ffffffff81950bb7-ffffffff81950c88: jhash2 (STB_LOCAL)
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
In kernel/futex.c (ffffffff81127f75)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/stackmap.c (ffffffff811d116e)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff81255339)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In mm/ksm.c (ffffffff8125ed1b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In ipc/util.c (ffffffff813d6ce6)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff814cd0f0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff8188a3fb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d64ff)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818da36d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8b95)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1edb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819428b7)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b453)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/udp.c (ffffffff8198559e)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81990410)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_obj_hashfn
  - net/ipv6/reassembly.c:ip6_key_hashfn
```
```
In net/ipv6/ip6mr.c (ffffffff8199f0cc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9d43)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819aca27)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff811337b5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff811df31d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff811e0c9e)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff81269719)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (ffffffff813f12d9)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff814e16a0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff818ab301)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819018ea)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81906dad)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff81917135)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fbdb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972987)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197dd13)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81987a3d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff819bbd0e)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff819c7d3a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (ffffffff819d5bec)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0863)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e352a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff8113e765)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff811f4cfd)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff811f689d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff812873ce)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff8141d58f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d4d0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/flow_dissector.c (ffffffff818f6c6d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_get_hash_perturb
  - net/core/flow_dissector.c:__skb_get_hash
  - net/core/flow_dissector.c:__skb_get_hash_symmetric
  - net/core/flow_dissector.c:flow_hash_from_keys
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8195f810)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8196804d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff81978b35)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff819824c8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e7128)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff819f17df)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81a2a758)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81a367fa)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f4b5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a520da)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff8114a2d5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff81201d0d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff8120385d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff81296fde)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff814373df)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b320)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81963960)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199eaed)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff819af4a5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8d3b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1e118)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a286af)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81a612ab)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81a6d31a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86145)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88cdd)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff8115abf5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8122b6b4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff812c7815)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158f3f0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a77774)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98da5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3862)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10188)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1ad24)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/route.c (ffffffff81b432a4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
```
In net/ipv6/udp.c (ffffffff81b59d29)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81b6582a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83d79)
Location: include/linux/jhash.h:116
Inline: True
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
In kernel/futex.c (ffffffff81156d45)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233725)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff812d3385)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff815abcd0)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a80644)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2d15)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadea2)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1e478)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2952b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/route.c (ffffffff81b51994)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
```
In net/ipv6/udp.c (ffffffff81b68389)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81b73f8a)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b935d9)
Location: include/linux/jhash.h:117
Inline: True
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
In kernel/futex.c (ffffffff81158165)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff812374e5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff812da0c5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b60cb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a69cd4)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8ddf5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98e69)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c134)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17166)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81b56687)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81b629ed)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b826f7)
Location: include/linux/jhash.h:117
Inline: True
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
In kernel/futex.c (ffffffff8117d075)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81271ab5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff81320e85)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c5eb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b232c4)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b48fe5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b5432b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcf16c)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb516)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/udp.c (ffffffff81c1c147)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81c2a47d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e7c7)
Location: include/linux/jhash.h:117
Inline: True
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
In kernel/futex/core.c (ffffffff811b2255)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a4cab)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In kernel/bpf/offload.c (ffffffff812bda90)
Location: include/linux/jhash.h:117
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff812c0c00)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8138dc25)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (ffffffff815936a0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9dcb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In lib/stackdepot.c (ffffffff8176f702)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cab464)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6485)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce24a0)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55d78)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d65158)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81d7225a)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/udp.c (ffffffff81db8929)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81dc883d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb426)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea9c0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def0d9)
Location: include/linux/jhash.h:117
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
In kernel/futex/core.c (ffffffff811f30c5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff81302a2b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In kernel/bpf/offload.c (ffffffff81320fa0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff813244a0)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134cd10)
Location: include/linux/jhash.h:117
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140c985)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (ffffffff8163c0e0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9fbb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In lib/stackdepot.c (ffffffff8189f247)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69144)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81e969c5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3419)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5dcf)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa47d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f204a8)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f300bb)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3de88)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/udp.c (ffffffff81f88969)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81f995ed)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fae026)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe220)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3179)
Location: include/linux/jhash.h:117
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
In kernel/futex/core.c (ffffffff81207845)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_hash
```
```
In kernel/bpf/hashtab.c (ffffffff81325e84)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff813311b4)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:hash
```
```
In kernel/bpf/offload.c (ffffffff813519b6)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff81354700)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137df73)
Location: include/linux/jhash.h:117
Inline: True
```
```
In mm/hugetlb.c (ffffffff8143fda5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (ffffffff81674705)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff8181933b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In lib/stackdepot.c (ffffffff818e1802)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: False
```
```
In net/netlink/af_netlink.c (ffffffff81ec4fdd)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef51f5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01c59)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04521)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08ca9)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7ffa6)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8ea21)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d783)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/udp.c (ffffffff81feb51c)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff81ff905d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200e7d2)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fb1d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024c5a)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/handshake/request.c (ffffffff820935d6)
Location: include/linux/jhash.h:117
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
In kernel/futex/core.c (ffffffff8121ea55)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_hash
```
```
In kernel/bpf/hashtab.c (ffffffff8134a3c4)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff81355754)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:hash
```
```
In kernel/bpf/offload.c (ffffffff81378e96)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff8137d070)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a71d3)
Location: include/linux/jhash.h:117
Inline: True
```
```
In mm/hugetlb.c (ffffffff81479c55)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
```
```
In ipc/util.c (ffffffff816b0ac5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e68b)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In lib/stackdepot.c (ffffffff8192886a)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:117
Inline: False
```
```
In net/netlink/af_netlink.c (ffffffff81f883bd)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb91a5)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5d19)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8847)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccfd4)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82046626)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205c731)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff8206aae3)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/udp.c (ffffffff820b91dc)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff820c6cdd)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dd762)
Location: include/linux/jhash.h:117
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eec4d)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3ec9)
Location: include/linux/jhash.h:117
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/handshake/request.c (ffffffff82169e86)
Location: include/linux/jhash.h:117
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
In kernel/futex.c (ffff8000101b6828)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffff80001028a16c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffff80001028bfd4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffff800010334e00)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffff80001051dbd8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffff800010636990)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: False
```
```
In net/core/flow_offload.c (ffff800010c08594)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4b7dc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f46c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a384)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccbea4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdead4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7e00)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffff800010d24728)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffff800010d34e88)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (ffff800010d44a50)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51de8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55bf8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (c0401074)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In kernel/bpf/stackmap.c (c04bb6a4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (c07dc6cc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5dab4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/ip_fragment.c (c0d6f8dc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (c0d79770)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0de429c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (c0def098)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (c0e2b58c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (c0e36d1c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c0e561f8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (c00000000021c240)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (c000000000335524)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (c00000000033810c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (c00000000040e4e4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (c000000000666fa0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (c0000000007dc7b0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: False
```
```
In net/core/flow_offload.c (c000000000cf2bcc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4b8fc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (c000000000d62f28)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f750)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb394)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb780)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (c000000000e09ed8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (c000000000e57000)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (c000000000e66af8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (c000000000e79518)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a9a0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e9ac)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffe00013c620)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffe0001be2a0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffe0001bfa6c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffe0002315e4)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffe0003853e2)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffe000463c60)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: False
```
```
In net/core/flow_offload.c (ffffffe0007863c8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9c22)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7d6c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d013c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00082080c)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b642)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffe000835600)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffe0008682d8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffe00087234a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (ffffffe00087f3ce)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4ac)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d2ea)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff811428f5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff811fa32d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff811fbe7d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8128f5be)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff8142f9bf)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523900)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81903930)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193e95d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f315)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958bab)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd7a8)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff819c7d3f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81a0093b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81a0c9aa)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a257d5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a2836d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff81135c55)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff811ed07d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff811eebcd)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8128128e)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff8142043f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513be0)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (ffffffff818bd760)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f845d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff81908e05)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191269b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197a598)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81984b2f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff819bd6fb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff819c976a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2595)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e512d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff811407a5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff811f80fd)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/bpf/stackmap.c (ffffffff811f9c4d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8128d3ce)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff8142bb5f)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151f990)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81954960)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8198faed)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199d02a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:hash_conntrack_raw
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a258a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9ae5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c337b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a28228)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a327bf)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81a6b3bb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81a7742a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90255)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9151a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:ip6frag_obj_hashfn
  - net/ipv6/netfilter/nf_conntrack_reasm.c:ip6frag_key_hashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93f1d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/futex.c (ffffffff8114d9c5)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/futex.c:hash_futex
```
```
In kernel/bpf/offload.c (ffffffff81206452)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/bpf/stackmap.c (ffffffff8120870d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In mm/hugetlb.c (ffffffff8129d196)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In ipc/util.c (ffffffff81442b75)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In lib/rhashtable.c (ffffffff81539270)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_jhash2
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/core/flow_offload.c (ffffffff8197661b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b248d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3915)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip4_obj_hashfn
  - net/ipv4/ip_fragment.c:ip4_key_hashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd04b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a2861b)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:116
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33858)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3e0ed)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/udp.c (ffffffff81a779cb)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/reassembly.c (ffffffff81a82e7a)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6frag_obj_hashfn
  - net/ipv6/reassembly.c:ip6frag_key_hashfn
```
```
In net/ipv6/ip6mr.c (ffffffff81a92418)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d4cc)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa006d)
Location: include/linux/jhash.h:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
