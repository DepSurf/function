# Function: <code>rht_bucket_nested</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146aed0)
Location: lib/rhashtable.c:1090
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8146aed0-ffffffff8146af31: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814971b0)
Location: lib/rhashtable.c:1093
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - security/apparmor/apparmorfs.c:aa_write_access
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_walk_next
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - net/sched/act_api.c:tcf_action_egdev_lookup
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff814971b0-ffffffff81497211: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc170)
Location: lib/rhashtable.c:1191
Inline: False
Direct callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - security/apparmor/apparmorfs.c:aa_write_access
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/sched/act_api.c:tcf_action_egdev_lookup
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff814cc170-ffffffff814cc1cc: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rhash_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0890)
Location: lib/rhashtable.c:1182
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - security/apparmor/apparmorfs.c:aa_write_access
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_lookup_one
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff814e0890-ffffffff814e090a: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150c9b2)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
  - net/sched/cls_api.c:tc_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8150c7a0-ffffffff8150c7b9: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a802)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8152a5f0-ffffffff8152a609: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158ef6d)
Location: lib/rhashtable.c:1203
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - ipc/util.c:ipc_findkey
  - net/core/xdp.c:__xdp_release_frame
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8158df30-ffffffff8158df49: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815abadd)
Location: lib/rhashtable.c:1203
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff815aaac0-ffffffff815aaad9: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b5fc4)
Location: lib/rhashtable.c:1203
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff815b56e0-ffffffff815b56f9: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8161c471)
Location: lib/rhashtable.c:1203
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:__rhashtable_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8161bb40-ffffffff8161bb59: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff816e9c0f)
Location: lib/rhashtable.c:1203
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff816e94d0-ffffffff816e94f3: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff817d9dcf)
Location: lib/rhashtable.c:1207
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff817d9620-ffffffff817d9643: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8181914f)
Location: lib/rhashtable.c:1207
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/handshake/request.c:handshake_req_hash_lookup
```
**Symbols:**

```
ffffffff81818820-ffffffff81818843: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8185e49f)
Location: lib/rhashtable.c:1207
Inline: True
Inline callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipc_findkey
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
  - net/handshake/request.c:handshake_req_hash_lookup
```
**Symbols:**

```
ffffffff8185db20-ffffffff8185db43: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010636960)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffff800010635a70-ffff800010635a94: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dc61c)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup_rcu
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
c07db98c-c07db9b0: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db860)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
c0000000007db2d0-c0000000007db318: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe00046337c)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffe000463234-ffffffe00046325e: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522de2)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81522bd0-ffffffff81522be9: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815130c2)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81512eb0-ffffffff81512ec9: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ee72)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_find_netdev
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/flow_offload.c:flow_indr_block_dev_lookup
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8151ec60-ffffffff8151ec79: rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8153888f)
Location: lib/rhashtable.c:1196
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - ipc/util.c:ipcget
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/flow_offload.c:flow_indr_block_call
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:netlink_lookup
  - net/ipv4/ipmr_base.c:mr_mfc_find_any
  - net/ipv4/ipmr_base.c:mr_mfc_find_any_parent
  - net/ipv4/ipmr_base.c:mr_mfc_find_parent
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
**Symbols:**

```
ffffffff81538600-ffffffff81538619: rht_bucket_nested (STB_GLOBAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct rhash_head **</code> ➡️ <code>struct rhash_lock_head **</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
