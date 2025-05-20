# Function: <code>__rhashtable_insert_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174cc63)
Location: include/linux/rhashtable.h:566
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
In security/apparmor/policy_unpack.c (ffffffff813bc01e)
Location: include/linux/rhashtable.h:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff817b902a)
Location: include/linux/rhashtable.h:567
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
In security/apparmor/policy_unpack.c (ffffffff813d353b)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff817e8af7)
Location: include/linux/rhashtable.h:669
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5266)
Location: include/linux/rhashtable.h:669
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
In security/apparmor/policy_unpack.c (ffffffff813e651f)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81808121)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff8186c224)
Location: include/linux/rhashtable.h:709
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb55a)
Location: include/linux/rhashtable.h:709
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
In ipc/util.c (ffffffff813a722b)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d701)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/act_api.c (ffffffff81882ada)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff81886f67)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ipmr.c (ffffffff818ecaf1)
Location: include/linux/rhashtable.h:709
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819502fa)
Location: include/linux/rhashtable.h:709
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
In ipc/util.c (ffffffff813d633a)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef63)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/act_api.c (ffffffff818d64ed)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818db08b)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8193946d)
Location: include/linux/rhashtable.h:725
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819428b7)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f0bb)
Location: include/linux/rhashtable.h:725
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9fbf)
Location: include/linux/rhashtable.h:725
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
In kernel/bpf/offload.c (ffffffff811df7ce)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff813f09ce)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be79)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/cls_api.c (ffffffff819018d6)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819079a4)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8196907f)
Location: include/linux/rhashtable.h:593
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972987)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198082c)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d5bdb)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0af0)
Location: include/linux/rhashtable.h:593
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f524d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141cf20)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d30)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/sched/cls_api.c (ffffffff8196296f)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81968bf1)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa3d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819dc3fe)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea55b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44c7b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f7cd)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81488d30-ffffffff81488f0a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8120224d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81436d70)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2be0)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81963e5b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8199f691)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a065cd)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a133ee)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a215ab)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b86b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8645d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff814a2be0-ffffffff814a2dba: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229760)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81486b80)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcec0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81a77a30)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5ae0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81b01950)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10860)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b74ee0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81130)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81229760-ffffffff81229926: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81486b80-ffffffff81486d44: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff814fcec0-ffffffff814fd0b3: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81a77a30-ffffffff81a77c73: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81af5ae0-ffffffff81af5e06: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b01950-ffffffff81b01c67: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b10860-ffffffff81b10ad1: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b74ee0-ffffffff81b751f7: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b81130-ffffffff81b8132e: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812312e0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814a4230)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a0d0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81a80900)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02950)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa30)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1eb50)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b83c50)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90960)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff812312e0-ffffffff812314b5: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff814a4230-ffffffff814a4403: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8151a0d0-ffffffff8151a2d2: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81a80900-ffffffff81a80b4d: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b02950-ffffffff81b02c77: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b0fa30-ffffffff81b0fd49: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b1eb50-ffffffff81b1edcb: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b83c50-ffffffff81b83f69: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b90960-ffffffff81b90b68: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235470)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff814aa150)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff815209e0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81a69f90)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee260)
Location: include/linux/rhashtable.h:697
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afd630)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c7e0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81b728e0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fb80)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81235470-ffffffff81235638: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff814aa150-ffffffff814aa316: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff815209e0-ffffffff81520bd5: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81a69f90-ffffffff81a6a1d1: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81aee260-ffffffff81aee574: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81afd630-ffffffff81afd940: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b0c7e0-ffffffff81b0ca47: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b728e0-ffffffff81b72bf0: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b7fb80-ffffffff81b7fd7c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126f610)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81502630)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8157eb80)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81b23580)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae610)
Location: include/linux/rhashtable.h:697
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf730)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcf9d0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a138)
Location: include/linux/rhashtable.h:697
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ce20)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b420)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8126f610-ffffffff8126f7d8: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81502630-ffffffff815027f6: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8157eb80-ffffffff8157ed75: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81b23580-ffffffff81b237c1: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81bae610-ffffffff81bae924: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81bbf730-ffffffff81bbfa40: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81bcf9d0-ffffffff81bcfc37: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81c3ce20-ffffffff81c3d130: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81c4b420-ffffffff81c4b61c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff812bdfb0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81593950)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d660)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81cabf30)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41810)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81d55d50)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68f70)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd7e93)
Location: include/linux/rhashtable.h:697
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb3f0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deadb0)
Location: include/linux/rhashtable.h:697
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff812bdfb0-ffffffff812be1e9: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81593950-ffffffff81593b79: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8161d660-ffffffff8161d8d1: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81cabf30-ffffffff81cac1e8: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81d41810-ffffffff81d41bd3: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81d55d50-ffffffff81d5607c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81d68f70-ffffffff81d6923a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81ddb3f0-ffffffff81ddb7bb: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81deadb0-ffffffff81deb001: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff81321bf0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d4e0)
Location: include/linux/rhashtable.h:705
Inline: True
```
```
In ipc/util.c (ffffffff8163c7e0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1110)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81e69b00)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a630)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f20480)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34240)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81fa988d)
Location: include/linux/rhashtable.h:705
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fadff0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe990)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81321bf0-ffffffff81321e37: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8134d4e0-ffffffff8134d81c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8163c7e0-ffffffff8163ca20: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff816d1110-ffffffff816d138d: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e69b00-ffffffff81e69dbb: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81f0a630-ffffffff81f0aa05: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81f20480-ffffffff81f20784: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81f34240-ffffffff81f3450e: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81fadff0-ffffffff81fae395: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81fbe990-ffffffff81fbebee: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff813511a0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e710)
Location: include/linux/rhashtable.h:705
Inline: True
```
```
In ipc/util.c (ffffffff81674960)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a020)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81ec5a80)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a160)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f80c80)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93e60)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a20d)
Location: include/linux/rhashtable.h:705
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200f460)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fca0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/handshake/request.c (ffffffff82092ea0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/handshake/request.c:handshake_req_submit
```
**Symbols:**

```
ffffffff813511a0-ffffffff8135142c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8137e710-ffffffff8137eaaf: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81674960-ffffffff81674bda: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8170a020-ffffffff8170a29d: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81ec5a80-ffffffff81ec5d6a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81f6a160-ffffffff81f6a535: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81f80c80-ffffffff81f80fab: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81f93e60-ffffffff81f9412e: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8200f460-ffffffff8200f81d: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff8201fca0-ffffffff8201ff6f: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff82092ea0-ffffffff820931e8: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffff81378600)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7970)
Location: include/linux/rhashtable.h:705
Inline: True
```
```
In ipc/util.c (ffffffff816b0d20)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81747b20)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/netlink/af_netlink.c (ffffffff81f88cd0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff82030810)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82047300)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061210)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d91ae)
Location: include/linux/rhashtable.h:705
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820de3f0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eedd0)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/handshake/request.c (ffffffff82169750)
Location: include/linux/rhashtable.h:705
Inline: True
Direct callers:
  - net/handshake/request.c:handshake_req_submit
```
**Symbols:**

```
ffffffff81378600-ffffffff8137888c: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff813a7970-ffffffff813a7d0f: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff816b0d20-ffffffff816b0f9a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff81747b20-ffffffff81747d9d: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff81f88cd0-ffffffff81f88fca: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff82030810-ffffffff82030be5: __rhashtable_insert_fast.constprop.0.isra.0 (STB_LOCAL)
ffffffff82047300-ffffffff8204762b: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff82061210-ffffffff820614de: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff820de3f0-ffffffff820de7ad: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff820eedd0-ffffffff820ef09f: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
ffffffff82169750-ffffffff82169a98: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffff800010289dc0)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffff80001051d3ec)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598910)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffff800010c08578)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4c9fc)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf428)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffff800010ccd968)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc9f8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d453ac)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52360)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffff800010598910-ffff800010598b9c: __rhashtable_insert_fast.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (c04b9de4)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c06d9810)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749b28)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (c0d216b8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5da84)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcad7c)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c0dd8a78)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c0de79d8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47fc4)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c0e531ac)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c0749b28-c0749e28: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (c000000000335c44)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (c000000000666550)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f870)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (c000000000cf2ba8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4a590)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda078)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (c000000000dea38c)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfccc0)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7aef0)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a518)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c00000000070f870-c00000000070fbc4: __rhashtable_insert_fast.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/bpf/offload.c (ffffffe0001bde64)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffe000384ccc)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52a8)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffe0007863b8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007b8998)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815208)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffe00081fe4e)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0b8)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe0008806dc)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889dfc)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffe0003e52a8-ffffffe0003e5476: __rhashtable_insert_fast.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa86d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142f350)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b1c0)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81903e2b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8193f501)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a636d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff819b2bee)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c3b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1aefb)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25aed)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8149b1c0-ffffffff8149b39a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ed5bd)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8141fdd0)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bbe0)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff818bdc5b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818f9001)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe2d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff8196f21e)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da2b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7cbb)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e28ad)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8148bbe0-ffffffff8148bdba: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f863d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff8142b4f0)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81497260)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81954e5b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81990691)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c0d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1d48e)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b6bb)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a8597b)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9056d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81497260-ffffffff8149743a: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81206d58)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In ipc/util.c (ffffffff81442452)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af330)
Location: include/linux/rhashtable.h:704
Inline: True
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In net/core/flow_offload.c (ffffffff81976e02)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2f60)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b4dc)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ipmr.c (ffffffff81a285f7)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36cfe)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a923ed)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d69d)
Location: include/linux/rhashtable.h:704
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff814af330-ffffffff814af581: __rhashtable_insert_fast.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
