# Function: <code>rht_bucket_nested_insert</code>

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
struct rhash_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b550)
Location: lib/rhashtable.c:1121
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8146b550-ffffffff8146b62c: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81497840)
Location: lib/rhashtable.c:1124
Inline: False
Direct callers:
  - ipc/util.c:ipc_addid
  - security/apparmor/policy_unpack.c:unpack_profile
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81497840-ffffffff8149791c: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc780)
Location: lib/rhashtable.c:1222
Inline: False
Direct callers:
  - ipc/util.c:ipc_addid
  - security/apparmor/policy_unpack.c:unpack_profile
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff814cc780-ffffffff814cc85c: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rhash_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0dd0)
Location: lib/rhashtable.c:1215
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - security/apparmor/policy_unpack.c:unpack_profile
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/netlink/af_netlink.c:netlink_insert
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff814e0dd0-ffffffff814e0e50: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150cca0)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8150cca0-ffffffff8150cd49: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152aaf0)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8152aaf0-ffffffff8152ab9e: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e130)
Location: lib/rhashtable.c:1214
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff8158e130-ffffffff8158e1d7: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815aacc0)
Location: lib/rhashtable.c:1214
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff815aacc0-ffffffff815aad67: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b57d0)
Location: lib/rhashtable.c:1214
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
**Symbols:**

```
ffffffff815b57d0-ffffffff815b5877: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1214
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
**Symbols:**

```
ffffffff81cdab20-ffffffff81cdab8c: rht_bucket_nested_insert.cold (STB_LOCAL)
ffffffff8161bc30-ffffffff8161bd09: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1214
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
**Symbols:**

```
ffffffff81e933f0-ffffffff81e9345c: rht_bucket_nested_insert.cold (STB_LOCAL)
ffffffff816e9600-ffffffff816e96f9: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1218
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
**Symbols:**

```
ffffffff8207855c-ffffffff820785c8: rht_bucket_nested_insert.cold (STB_LOCAL)
ffffffff817d9780-ffffffff817d9879: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1218
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
**Symbols:**

```
ffffffff820f8ad2-ffffffff820f8b44: rht_bucket_nested_insert.cold (STB_LOCAL)
ffffffff81818b30-ffffffff81818bf4: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1218
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
**Symbols:**

```
ffffffff821d65f3-ffffffff821d6665: rht_bucket_nested_insert.cold (STB_LOCAL)
ffffffff8185de60-ffffffff8185df24: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010635c48)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffff800010635c48-ffff800010635cfc: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dbbd4)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c07dbbd4-c07dbc9c: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007dc0c0)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c0000000007dc0c0-c0000000007dc1f0: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe0004636b2)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffe0004636b2-ffffffe000463752: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815230d0)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff815230d0-ffffffff8152317e: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815133b0)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff815133b0-ffffffff8151345e: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151f160)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff8151f160-ffffffff8151f20e: rht_bucket_nested_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rhash_lock_head **rht_bucket_nested_insert(struct rhashtable *ht, struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81538b80)
Location: lib/rhashtable.c:1207
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - ipc/util.c:ipc_addid
  - lib/rhashtable.c:rhashtable_insert_slow
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/netlink/af_netlink.c:__netlink_insert
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
ffffffff81538b80-ffffffff81538c2e: rht_bucket_nested_insert (STB_GLOBAL)
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
