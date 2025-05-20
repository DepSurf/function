# Function: <code>rht_bucket_insert</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813e66a2)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146b6ae)
Location: include/linux/rhashtable.h:425
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81808174)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c293)
Location: include/linux/rhashtable.h:425
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb5b8)
Location: include/linux/rhashtable.h:425
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
In ipc/util.c (ffffffff813a728d)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d886)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8149799e)
Location: include/linux/rhashtable.h:425
Inline: True
```
```
In net/sched/act_api.c (ffffffff81882b52)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff81886fbe)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818ecb60)
Location: include/linux/rhashtable.h:425
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950358)
Location: include/linux/rhashtable.h:425
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
In ipc/util.c (ffffffff813d63c5)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143efbc)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cc8ca)
Location: include/linux/rhashtable.h:441
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d6589)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818db0e3)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819394c4)
Location: include/linux/rhashtable.h:441
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8194293f)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f1b7)
Location: include/linux/rhashtable.h:441
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819aa03c)
Location: include/linux/rhashtable.h:441
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
In kernel/bpf/offload.c (ffffffff811df861)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0a58)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bed1)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e0eba)
Location: include/linux/rhashtable.h:302
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81901970)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819079f6)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819690db)
Location: include/linux/rhashtable.h:302
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972a0b)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980890)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5cde)
Location: include/linux/rhashtable.h:302
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0b67)
Location: include/linux/rhashtable.h:302
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
In kernel/bpf/offload.c (ffffffff811f5284)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cf52)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d75)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d728)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/sched/cls_api.c (ffffffff819629a5)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81968c17)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa7d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc44a)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea596)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44cd3)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f7f7)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff81202284)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436da2)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c25)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b578)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81963e9d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199f6b7)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0660d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1343a)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a215e6)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b8c3)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86487)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff8122979e)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff81486bbd)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf0b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ebb0)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a77ab6)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5b5b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b019a3)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108c0)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b74f33)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81171)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff8123131e)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff814a426d)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a11b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab710)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a80986)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b029ca)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa83)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebb0)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83ca3)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b909a1)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff812354aa)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff814aa189)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a2b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b6575)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81a6a016)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee2e2)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd689)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c841)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72939)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fbc1)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff8126f64a)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff81502669)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebcb)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161cabd)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81b23606)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae692)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf789)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa31)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a176)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ce79)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b461)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff812bdfeb)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff8159398b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6bd)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea2f0)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81cabfbf)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418a0)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55ddd)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68fd4)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7ed3)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb4f2)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deadf5)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff81321c28)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d52c)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff8163c81c)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d116e)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da515)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81e69b8f)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6b6)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20508)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f342a4)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa98c5)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae0ee)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe9d1)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff8135121b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e79a)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff816749d4)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a07e)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff818197b7)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b29)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a1e6)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80d0a)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93ec4)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a245)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200f55b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fd1b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/handshake/request.c (ffffffff82092f2a)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff8137867b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a79fa)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In ipc/util.c (ffffffff816b0d94)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747b7e)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185eb07)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In net/netlink/af_netlink.c (ffffffff81f88d89)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030896)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204738a)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061274)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d91e6)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820de4eb)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eee4b)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/handshake/request.c (ffffffff821697da)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffff800010289e58)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d46c)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598964)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffff800010636d90)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffff800010c0860c)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4ca28)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf454)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010ccd9f4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdca20)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d454b0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffff800010d523e4)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (c04b9e24)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d9848)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749b94)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (c07dc9e4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c0d216f0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5db18)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcadc4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd8ab0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de7a30)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47ffc)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c0e531f4)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (c000000000335ce8)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c0000000006665d8)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f8e8)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcb80)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (c000000000cf2c4c)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4a5d0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda0c0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea428)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd04)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7b034)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a5a4)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffe0001bdefa)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384d52)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52e0)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640e8)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffe00078644e)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b89c2)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe00081522a)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe00081feea)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0e0)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe000880826)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889e90)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff811fa8a4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f382)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b205)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523b58)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81903e6d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8193f527)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63ad)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b2c3a)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c76)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1af53)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25b17)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff811ed5f4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fe02)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc25)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513e38)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff818bdc9d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818f9027)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe6d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f26a)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da66)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7d13)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e28d7)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff811f8674)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b522)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814972a5)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fbe8)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81954e9d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819906b7)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c4d)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d4da)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b6f6)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a859d3)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90597)
Location: include/linux/rhashtable.h:301
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
In kernel/bpf/offload.c (ffffffff81206dca)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814424b4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af37d)
Location: include/linux/rhashtable.h:301
Inline: True
```
```
In lib/rhashtable.c (ffffffff815394e1)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In net/core/flow_offload.c (ffffffff81976e78)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2f7c)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b526)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a28678)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d3e)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a924e4)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d700)
Location: include/linux/rhashtable.h:301
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
