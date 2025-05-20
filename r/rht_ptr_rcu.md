# Function: <code>rht_ptr_rcu</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4d73)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8141d603)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ce66)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150ca64)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81930056)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
```
In net/sched/cls_api.c (ffffffff8195f882)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff819688ae)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfdce)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819de9e1)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9c77)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f522)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (ffffffff81201d83)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81437453)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff81496b36)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152a8b4)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff819622b6)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff819639d2)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199f34e)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0695e)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15a91)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20cc7)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a861b2)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (ffffffff81228e89)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In ipc/util.c (ffffffff814866a8)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff814eed3b)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158eeb5)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a363fb)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
```
```
In net/netlink/af_netlink.c (ffffffff81a78708)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6394)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06603)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12b64)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81695)
Location: include/linux/rhashtable.h:366
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
In kernel/bpf/offload.c (ffffffff81230a6d)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a3c8b)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c1b0)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In lib/rhashtable.c (ffffffff815aba25)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a37be3)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a81a13)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81b03204)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b147f3)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b210e4)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90eb4)
Location: include/linux/rhashtable.h:366
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
In kernel/bpf/offload.c (ffffffff81234c18)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814a9c86)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff81512b3b)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b5f07)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81a1ed6e)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6ab0a)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee9b2)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81b025ef)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ed0f)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b800af)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff8126ed34)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81502136)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8157073b)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c3b6)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81ad2e0e)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b2410a)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81baed82)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc455f)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd210f)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81c3a7e4)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b95f)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (ffffffff812be5e6)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff81593754)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c5a1)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In lib/rhashtable.c (ffffffff816e9b34)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81c5111d)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81cac768)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d420d5)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81d595e0)
Location: include/linux/rhashtable.h:366
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d686b4)
Location: include/linux/rhashtable.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81dd8670)
Location: include/linux/rhashtable.h:366
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
In net/ipv6/seg6_hmac.c (ffffffff81deb340)
Location: include/linux/rhashtable.h:366
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
In kernel/bpf/offload.c (ffffffff81321288)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d15e)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In ipc/util.c (ffffffff8163c1a4)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816bec85)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In lib/rhashtable.c (ffffffff817d9cf4)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81e05dd6)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6a368)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af15)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23a20)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33754)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff81faa080)
Location: include/linux/rhashtable.h:373
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
In net/ipv6/seg6_hmac.c (ffffffff81fbef30)
Location: include/linux/rhashtable.h:373
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
In kernel/bpf/offload.c (ffffffff81351a2a)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dfee)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In ipc/util.c (ffffffff81674772)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7748)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In lib/rhashtable.c (ffffffff81819074)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81e78ad8)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81ec6337)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aa58)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83570)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92ad4)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff8200a9c7)
Location: include/linux/rhashtable.h:373
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
In net/ipv6/seg6_hmac.c (ffffffff8201fb85)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82093647)
Location: include/linux/rhashtable.h:373
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
In kernel/bpf/offload.c (ffffffff81378f0a)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a724e)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In ipc/util.c (ffffffff816b0b32)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - ipc/util.c:ipc_findkey
```
```
In security/apparmor/apparmorfs.c (ffffffff817344bb)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In lib/rhashtable.c (ffffffff8185e3c4)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81f389a8)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
```
In net/netlink/af_netlink.c (ffffffff81f895a8)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82031108)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr_base.c (ffffffff82049c20)
Location: include/linux/rhashtable.h:373
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d137)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ioam6.c (ffffffff820d9997)
Location: include/linux/rhashtable.h:373
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
In net/ipv6/seg6_hmac.c (ffffffff820eecb5)
Location: include/linux/rhashtable.h:373
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
```
In net/handshake/request.c (ffffffff82169ef7)
Location: include/linux/rhashtable.h:373
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
In kernel/bpf/offload.c (ffff80001028a6a4)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffff80001051dc64)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffff80001058cd30)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffff8000106362f8)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffff800010c06580)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffff800010c07f60)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffff800010c4cea0)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf7ec)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1648)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde6e8)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52738)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In kernel/bpf/offload.c (c04b9764)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c06da0a4)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c073da14)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (c07dc240)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (c0d1f63c)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c0d20dd4)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5dff0)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c0dcb1c0)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (c0ddb518)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c0de6b30)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c0e52ac4)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (c000000000336160)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (c000000000667030)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (c0000000006fed78)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (c0000000007db990)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (c000000000cf0a4c)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (c000000000cf234c)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (c000000000d4bc88)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (c000000000dda598)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (c000000000def7f4)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (c000000000dfe8ec)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ada0)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffe0001be6e0)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffe000385488)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db01e)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004634e0)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffe000784b1a)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786012)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffe0007b9d92)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffe0008154cc)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffe000822bfa)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dc38)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a77c)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811fa3a3)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142fa33)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f116)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff81522e94)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81902286)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff819039a2)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8193f1be)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819a66fe)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff819b5121)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0357)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25842)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (ffffffff811ed0f3)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff814204b3)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8147fb36)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513174)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff818bc0b6)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff818bd7d2)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818f8cbe)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff819601be)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81971751)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d147)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2602)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (ffffffff811f8173)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
```
```
In ipc/util.c (ffffffff8142bbd3)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b1b6)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151ef24)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff819532b6)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
```
In net/core/flow_offload.c (ffffffff819549d2)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8199034e)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10f9e)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f9c1)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2add7)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a902c2)
Location: include/linux/rhashtable.h:367
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
In kernel/bpf/offload.c (ffffffff812064c8)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In ipc/util.c (ffffffff81442be7)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
```
In security/apparmor/apparmorfs.c (ffffffff814a30ab)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In lib/rhashtable.c (ffffffff81538944)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
```
```
In net/core/xdp.c (ffffffff81974dbe)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/flow_offload.c (ffffffff81976690)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b2c3e)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b901)
Location: include/linux/rhashtable.h:367
Inline: True
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2aec1)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36406)
Location: include/linux/rhashtable.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d536)
Location: include/linux/rhashtable.h:367
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
