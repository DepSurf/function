# Function: <code>rhashtable_compare</code>

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
In lib/rhashtable.c (ffffffff81400ccc)
Location: include/linux/rhashtable.h:508
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:508
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
In security/apparmor/apparmorfs.c (ffffffff813ae5a0)
Location: include/linux/rhashtable.h:509
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:509
Inline: True
```
```
In lib/rhashtable.c (ffffffff81448466)
Location: include/linux/rhashtable.h:509
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:509
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff813c53b5)
Location: include/linux/rhashtable.h:550
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:550
Inline: True
```
```
In lib/rhashtable.c (ffffffff81465f88)
Location: include/linux/rhashtable.h:550
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:550
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:550
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff813db6d9)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
```
```
In lib/rhashtable.c (ffffffff8146b157)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:590
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
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
In ipc/util.c (ffffffff813a7948)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8140218a)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
```
```
In lib/rhashtable.c (ffffffff8149743e)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
```
```
In net/sched/act_api.c (ffffffff8188277e)
Location: include/linux/rhashtable.h:590
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:590
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:590
Inline: False
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
In ipc/util.c (ffffffff813d6d82)
Location: include/linux/rhashtable.h:606
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81433096)
Location: include/linux/rhashtable.h:606
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In lib/rhashtable.c (ffffffff814cc65a)
Location: include/linux/rhashtable.h:606
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d5de0)
Location: include/linux/rhashtable.h:606
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819395c8)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81944dcf)
Location: include/linux/rhashtable.h:606
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:606
Inline: True
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
In kernel/bpf/offload.c (ffffffff811df3cd)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff813f1382)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8144fd85)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In lib/rhashtable.c (ffffffff814e09ca)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_lookup_one
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818ff0b3)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819691a9)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81974f4e)
Location: include/linux/rhashtable.h:467
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:467
Inline: True
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
In kernel/bpf/offload.c (ffffffff811f4daf)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d637)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ced3)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d7b9)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8195f8b6)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfba0)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819deac5)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff81201dbf)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437487)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81496ba3)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b609)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81963a06)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06730)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15b75)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff81228edf)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In ipc/util.c (ffffffff814866e0)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff814eed9a)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:571
Inline: False
```
```
In lib/rhashtable.c (ffffffff8158eb44)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5c57)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01bd2)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0665f)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b75162)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:571
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
In kernel/bpf/offload.c (ffffffff81230a99)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3cb3)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c214)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:571
Inline: False
```
```
In lib/rhashtable.c (ffffffff815ab6a4)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02ac8)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fb88)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b1484f)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83da8)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:571
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
In kernel/bpf/offload.c (ffffffff81234c44)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9cae)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81512b9f)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:571
Inline: False
```
```
In lib/rhashtable.c (ffffffff815b6508)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee3d3)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd78a)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0264b)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72a3a)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:571
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
In kernel/bpf/offload.c (ffffffff8126ed60)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8150215e)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8157079f)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:571
Inline: False
```
```
In lib/rhashtable.c (ffffffff8161ca4b)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae783)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf88a)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc45bb)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c39657)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3cf7a)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:571
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
In kernel/bpf/offload.c (ffffffff812be61d)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593781)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c622)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:571
Inline: False
```
```
In lib/rhashtable.c (ffffffff816ea286)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4217d)
Location: include/linux/rhashtable.h:571
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59641)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:571
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:571
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
In kernel/bpf/offload.c (ffffffff813212b7)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d191)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In ipc/util.c (ffffffff8163c1d1)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bed07)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In lib/rhashtable.c (ffffffff817da4a5)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0afbd)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a81)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:579
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
In kernel/bpf/offload.c (ffffffff81351a63)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e033)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In ipc/util.c (ffffffff816747a0)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f77bd)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In lib/rhashtable.c (ffffffff81818a14)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6ab70)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81f835f9)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/handshake/request.c (ffffffff82093677)
Location: include/linux/rhashtable.h:579
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
In kernel/bpf/offload.c (ffffffff81378f43)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7293)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In ipc/util.c (ffffffff816b0b60)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81734530)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In lib/rhashtable.c (ffffffff8185dd14)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv4/inet_fragment.c (ffffffff82031220)
Location: include/linux/rhashtable.h:579
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff82049ca9)
Location: include/linux/rhashtable.h:579
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:579
Inline: False
```
```
In net/handshake/request.c (ffffffff82169f27)
Location: include/linux/rhashtable.h:579
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
In kernel/bpf/offload.c (ffff80001028a6cc)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc94)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffff80001058ce74)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffff800010636cc4)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffff800010c07f88)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf59c)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffff800010cd172c)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (c04b9c6c)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da218)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c073da88)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: False
```
```
In lib/rhashtable.c (c07dca5c)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (c0d1fb60)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c0d20eb0)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5e0dc)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c0dcb044)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (c0ddb604)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de7b40)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c0e52b68)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (c000000000336198)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000667060)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c0000000006fef64)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcc64)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (c000000000cf2388)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (c000000000dda224)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (c000000000def924)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffe0001be6fe)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe0003854ae)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db1ae)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004642ee)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffe000786032)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffe0008152ec)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffe000822caa)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff811fa3df)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa67)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f183)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523be9)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffff819039d6)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff819a64d0)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5205)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff811ed12f)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814204e7)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fba3)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513ec9)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffff818bd806)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ff90)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81971835)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff811f81af)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bc07)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b223)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fc79)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81954a06)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10d70)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1faa5)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
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
In kernel/bpf/offload.c (ffffffff81206504)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442c1b)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814a311d)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In lib/rhashtable.c (ffffffff81539577)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/xdp.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/core/flow_offload.c (ffffffff819766d6)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b640)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2afa5)
Location: include/linux/rhashtable.h:578
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/rhashtable.h:578
Inline: True
```
</details>
</li>
</ul>

## Differences
