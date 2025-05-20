# Function: <code>rht_grow_above_max</code>

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
In lib/rhashtable.c (ffffffff81400bff)
Location: include/linux/rhashtable.h:298
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174cccb)
Location: include/linux/rhashtable.h:298
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In security/apparmor/policy_unpack.c (ffffffff813bc118)
Location: include/linux/rhashtable.h:298
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81448395)
Location: include/linux/rhashtable.h:298
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff817b9098)
Location: include/linux/rhashtable.h:298
Inline: True
Inline callers:
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
In security/apparmor/policy_unpack.c (ffffffff813d35f2)
Location: include/linux/rhashtable.h:315
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146616b)
Location: include/linux/rhashtable.h:315
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e8c10)
Location: include/linux/rhashtable.h:315
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a53aa)
Location: include/linux/rhashtable.h:315
Inline: True
Inline callers:
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
In security/apparmor/policy_unpack.c (ffffffff813e6523)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146b668)
Location: include/linux/rhashtable.h:329
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818082ac)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c3bb)
Location: include/linux/rhashtable.h:329
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb640)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
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
In ipc/util.c (ffffffff813a72d0)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d705)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81497958)
Location: include/linux/rhashtable.h:329
Inline: True
```
```
In net/sched/act_api.c (ffffffff81882b94)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff8188710e)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818ecc95)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff8195043d)
Location: include/linux/rhashtable.h:329
Inline: True
Inline callers:
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
In ipc/util.c (ffffffff813d6407)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143eff8)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cc89b)
Location: include/linux/rhashtable.h:338
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d65cb)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818db226)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81939507)
Location: include/linux/rhashtable.h:338
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81942b80)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f448)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819aa122)
Location: include/linux/rhashtable.h:338
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811df8aa)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0a9a)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf0d)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e0e8b)
Location: include/linux/rhashtable.h:204
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819019b2)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81907ad4)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819691ee)
Location: include/linux/rhashtable.h:204
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972c4c)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198094d)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f6f)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0c36)
Location: include/linux/rhashtable.h:204
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
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
In kernel/bpf/offload.c (ffffffff811f52ed)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cfbb)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488ddd)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d82f)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/sched/cls_api.c (ffffffff81962a0e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81968cac)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfbeb)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc819)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea69e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44fec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f8c6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff812022ed)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436e0b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c8d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b67f)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81963f06)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199f74c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0677b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a13809)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a216ee)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bbdc)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86556)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff81229808)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff81486c27)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf75)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ec56)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a77b45)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5ca2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01ac8)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b109a9)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b75058)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8121c)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff81231388)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff814a42d7)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a185)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab7b6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a80a15)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02b13)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fbd1)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ec9e)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83df1)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90a51)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff81235513)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff814aa1f2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a94)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b661b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a6a0a5)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee426)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd7d3)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c929)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72a83)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fc71)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff8126f6b3)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff815026d2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec34)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161cb63)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81b23695)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae7d6)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf8d3)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfb19)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a251)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3cfc3)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b511)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff812be05c)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff815939fc)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d72e)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea363)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81cac055)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41a50)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55e7b)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d690d5)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7fda)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb5a0)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaec3)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff81321c9b)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d682)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff8163c890)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11e2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da586)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81e69c29)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a85d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f205ab)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f343ab)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa99d5)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae1a2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeaad)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff8135128e)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e9ab)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff81674a4a)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0f2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff818197ef)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81ec5bc1)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a38d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80d93)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93fcb)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a354)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200f5e9)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fe0a)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/handshake/request.c (ffffffff8209311a)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffffffff813786ee)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7c0b)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In ipc/util.c (ffffffff816b0e0a)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bf2)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185eb3f)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81f88e21)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030a3d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82047413)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206137b)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d92f5)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820de579)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eef3a)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In net/handshake/request.c (ffffffff821699ca)
Location: include/linux/rhashtable.h:220
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
In kernel/bpf/offload.c (ffff800010289ee4)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d4ec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff8000105989fc)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffff800010636d3c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffff800010c086ec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4cb74)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf5e0)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010ccdde0)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcb30)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d45844)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52528)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (c04b9ec8)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d98ec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749c38)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (c07dcaf8)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c0d21794)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dbe4)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcaf2c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd8e74)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de7bb0)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e4834c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c0e53360)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (c000000000335d7c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c00000000066666c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f97c)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcd10)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c000000000cf2cdc)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4a74c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda270)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea8b4)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfce3c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7b2fc)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a72c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffe0001bdf56)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384db6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5336)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffe000464348)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffe0007864ae)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b8a9e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815318)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe00082023e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c1b6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe000880aa4)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889f66)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811fa90d)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f3eb)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b26d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523c5f)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81903ed6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8193f5bc)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a651b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b3009)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0d7e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b26c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25be6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811ed65d)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fe6b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc8d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513f3f)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff818bdd06)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818f90bc)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ffdb)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f639)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197db6e)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d802c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e29a6)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811f86dd)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b58b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149730d)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fcef)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81954f06)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199074c)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10dbb)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d8a9)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b7fe)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a85cec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90666)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff81206e3b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81442526)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3ec)
Location: include/linux/rhashtable.h:220
Inline: True
```
```
In lib/rhashtable.c (ffffffff815395ed)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81976eea)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b3019)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b68b)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a28a8a)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36e77)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a92815)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d7ec)
Location: include/linux/rhashtable.h:220
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
