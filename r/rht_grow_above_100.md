# Function: <code>rht_grow_above_100</code>

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
In lib/rhashtable.c (ffffffff81400c43)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff8174cd3f)
Location: include/linux/rhashtable.h:286
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
In security/apparmor/policy_unpack.c (ffffffff813bc403)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814483d8)
Location: include/linux/rhashtable.h:286
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/netlink/af_netlink.c (ffffffff817b9118)
Location: include/linux/rhashtable.h:286
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
In security/apparmor/policy_unpack.c (ffffffff813d3685)
Location: include/linux/rhashtable.h:303
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81466184)
Location: include/linux/rhashtable.h:303
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e8cae)
Location: include/linux/rhashtable.h:303
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a53eb)
Location: include/linux/rhashtable.h:303
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
In security/apparmor/policy_unpack.c (ffffffff813e6531)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146b679)
Location: include/linux/rhashtable.h:317
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818082b6)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c3cd)
Location: include/linux/rhashtable.h:317
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb64e)
Location: include/linux/rhashtable.h:317
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
In ipc/util.c (ffffffff813a72e3)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d713)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81497969)
Location: include/linux/rhashtable.h:317
Inline: True
```
```
In net/sched/act_api.c (ffffffff81882ba2)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff81887118)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818ecca7)
Location: include/linux/rhashtable.h:317
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950447)
Location: include/linux/rhashtable.h:317
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
In ipc/util.c (ffffffff813d641a)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f005)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cc8af)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d65dc)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818db237)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81939516)
Location: include/linux/rhashtable.h:326
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81942b96)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f45a)
Location: include/linux/rhashtable.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819aa12f)
Location: include/linux/rhashtable.h:326
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
In kernel/bpf/offload.c (ffffffff811df8bc)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0aad)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf1a)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e0e9f)
Location: include/linux/rhashtable.h:192
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819019c4)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81907ae5)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819691fd)
Location: include/linux/rhashtable.h:192
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972c62)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198095f)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f81)
Location: include/linux/rhashtable.h:192
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0c43)
Location: include/linux/rhashtable.h:192
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
In kernel/bpf/offload.c (ffffffff811f52ff)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cfca)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488df0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d840)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/sched/cls_api.c (ffffffff81962a20)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81968cbf)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfbfa)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc82f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea6b0)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a45002)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f8d5)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff812022ff)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436e1a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2ca0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b690)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81963f18)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199f75f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0678a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1381f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21700)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bbf2)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86565)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff8122981a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff81486c3a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf88)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ec69)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a77b58)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5cb5)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01adb)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b109bb)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7506b)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8122f)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff8123139a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff814a42ea)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a198)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab7c9)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a80a28)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02b24)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fbe4)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ecb0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83e04)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90a64)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff81235525)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff814aa205)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520aa7)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b662e)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a6a0b8)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee437)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd7e6)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c93b)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72a96)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fc84)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff8126f6c5)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff815026e5)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec47)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161cb76)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81b236a8)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae7e7)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf8e6)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfb2b)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a267)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3cfd6)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b524)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff812be06e)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff81593a0b)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d73d)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea372)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81cac066)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41a5f)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55e8a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d690e7)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7fec)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb5b3)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaed2)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff81321cad)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d694)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff8163c89f)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11f1)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da595)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81e69c3a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a86c)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f205ba)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f343bd)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa99e7)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae1b5)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeabc)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff813512a0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e9bd)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff81674a59)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a101)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819802)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81ec5bd0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a39c)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80da4)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93fdd)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a366)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200f5fa)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fe1d)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/handshake/request.c (ffffffff8209312c)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff81378700)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7c1d)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In ipc/util.c (ffffffff816b0e19)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c01)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185eb52)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81f88e30)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030a4c)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82047424)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206138d)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9307)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820de58a)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eef4d)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In net/handshake/request.c (ffffffff821699dc)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffff800010289ef8)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d4fc)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598a0c)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffff800010636d4c)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffff800010c086fc)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4cb84)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf5f0)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010ccddf0)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcb40)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d45854)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52538)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (c04b9ed8)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d98fc)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749c48)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (c07dcb08)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c0d217a4)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dbf4)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcaf3c)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd8e84)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de7bc0)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e4835c)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c0e53370)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (c000000000335d94)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666680)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f990)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcd20)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c000000000cf2cf4)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4a760)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda284)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea8c8)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfce54)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7b310)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a740)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffe0001bdf64)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384dc4)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5342)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffe000464356)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffe0007864bc)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b8aac)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815326)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe000820250)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c1c4)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe000880ab6)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889f74)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff811fa91f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f3fa)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b280)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523c70)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81903ee8)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8193f5cf)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a652a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b301f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0d90)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b282)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25bf5)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff811ed66f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fe7a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bca0)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513f50)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff818bdd18)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818f90cf)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ffea)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f64f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197db80)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d8042)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e29b5)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff811f86ef)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b59a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81497320)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fd00)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81954f18)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199075f)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10dca)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d8bf)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b810)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a85d02)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90675)
Location: include/linux/rhashtable.h:208
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
In kernel/bpf/offload.c (ffffffff81206e4d)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81442535)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3ff)
Location: include/linux/rhashtable.h:208
Inline: True
```
```
In lib/rhashtable.c (ffffffff815395fe)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81976efc)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b302c)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b69a)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a28aa0)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36e89)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a9282b)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d7fd)
Location: include/linux/rhashtable.h:208
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
