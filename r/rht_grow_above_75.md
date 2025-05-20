# Function: <code>rht_grow_above_75</code>

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
In lib/rhashtable.c (ffffffff8140058e)
Location: include/linux/rhashtable.h:260
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff8174ce5a)
Location: include/linux/rhashtable.h:260
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
In security/apparmor/policy_unpack.c (ffffffff813bc49a)
Location: include/linux/rhashtable.h:260
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81447a3e)
Location: include/linux/rhashtable.h:260
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817b9236)
Location: include/linux/rhashtable.h:260
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
In security/apparmor/policy_unpack.c (ffffffff813d36a4)
Location: include/linux/rhashtable.h:277
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff81466a20)
Location: include/linux/rhashtable.h:277
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff817e8ce8)
Location: include/linux/rhashtable.h:277
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a541b)
Location: include/linux/rhashtable.h:277
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
In security/apparmor/policy_unpack.c (ffffffff813e6701)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8146c27e)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff818082e9)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c40b)
Location: include/linux/rhashtable.h:291
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb671)
Location: include/linux/rhashtable.h:291
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
In ipc/util.c (ffffffff813a735e)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d8e7)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff8149857d)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff81882bea)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff81887146)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818ecce4)
Location: include/linux/rhashtable.h:291
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff8195046d)
Location: include/linux/rhashtable.h:291
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
In ipc/util.c (ffffffff813d6494)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f040)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814cd75d)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/act_api.c (ffffffff818d6649)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818db273)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819395fa)
Location: include/linux/rhashtable.h:300
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81942bd7)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f495)
Location: include/linux/rhashtable.h:300
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819aa15b)
Location: include/linux/rhashtable.h:300
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
In kernel/bpf/offload.c (ffffffff811df8de)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f0b2b)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf55)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In lib/rhashtable.c (ffffffff814e194f)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/cls_api.c (ffffffff81901afe)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81907b6f)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819692b6)
Location: include/linux/rhashtable.h:166
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972ca3)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980999)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5fbc)
Location: include/linux/rhashtable.h:166
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0c6f)
Location: include/linux/rhashtable.h:166
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
In kernel/bpf/offload.c (ffffffff811f5376)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141d070)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e68)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d914)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/sched/cls_api.c (ffffffff81962b14)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81968d0f)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfc4b)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc890)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea77a)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a45067)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f91b)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81202376)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436ec0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2d18)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b764)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffff81964018)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199f7af)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a067db)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a13880)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a217ca)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7bc57)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a865ab)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81229893)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff81486cb4)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd00d)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ecbb)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81a77bac)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5d1b)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01b4b)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10a10)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b750db)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81283)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81231418)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff814a4369)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a222)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab81b)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81a80a7c)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02b88)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fc50)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ed05)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83e70)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90ab8)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff8123559f)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff814aa280)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81520b2d)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b667e)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81a6a104)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee493)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd84a)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c988)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72afa)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fcd0)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff8126f73f)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff81502760)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8157eccd)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161cbcc)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81b236f4)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae843)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf94a)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfb78)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a338)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d03a)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b570)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff812be10e)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff81593aa7)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d7ee)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea3e1)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81cac0b8)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41ac5)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55ee4)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69138)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd80d5)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb612)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaf20)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81321d4e)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d6ef)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff8163c93d)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d129e)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff817da5f7)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81e69c8a)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a8d2)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f20612)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3440d)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa9ac8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae212)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeb08)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81351341)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137ea19)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff81674af7)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a1ae)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819864)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81ec5c1f)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a402)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80dfe)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9402d)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a44f)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200f655)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fe71)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/handshake/request.c (ffffffff82093179)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff813787a1)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7c79)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In ipc/util.c (ffffffff816b0eb7)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747cae)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185ebb4)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/netlink/af_netlink.c (ffffffff81f88e7f)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030ab2)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204747e)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820613dd)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d93f0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820de5e5)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eefa1)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In net/handshake/request.c (ffffffff82169a29)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffff80001028a018)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d5dc)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598ae0)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffff800010636df8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffff800010c08764)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4cbd8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf64c)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010cce020)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcc18)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d45a84)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffff800010d5258c)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (c04b9f88)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d99e4)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749d0c)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (c07dcbd8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (c0d21958)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dc60)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcafac)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd9160)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de7cf4)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e486ec)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c0e533dc)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (c000000000335e6c)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666748)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070fa7c)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcd8c)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (c000000000cf2e80)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4a7d0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda2e8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea934)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcec8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7b37c)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a7b0)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffe0001bdfe6)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384e86)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e53ca)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004643f0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffe000786586)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b8af6)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815372)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe0008202a0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c206)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe000880b06)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889fbe)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff811fa996)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f4a0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b2f8)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523d44)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffff81903fe8)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8193f61f)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a657b)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b3080)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0e5a)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b2e7)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25c3b)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff811ed6e6)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141ff20)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bd18)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff81514024)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffff818bde18)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818f911f)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8196003b)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f6b0)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197dc4a)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d80a7)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e29fb)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff811f8766)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b640)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81497398)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fdd4)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffff81955018)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819907af)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10e1b)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d920)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b8da)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a85d67)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a906bb)
Location: include/linux/rhashtable.h:182
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
In kernel/bpf/offload.c (ffffffff81206ee6)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814425f9)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af49f)
Location: include/linux/rhashtable.h:182
Inline: True
```
```
In lib/rhashtable.c (ffffffff815396ed)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In net/core/flow_offload.c (ffffffff8197701c)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b3089)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b6f9)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a28b12)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36f7e)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a9289d)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d854)
Location: include/linux/rhashtable.h:182
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
