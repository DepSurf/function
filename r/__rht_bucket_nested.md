# Function: <code>__rht_bucket_nested</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150c740)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff8150c740-ffffffff8150c793: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a590)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff8152a590-ffffffff8152a5e3: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158ded0)
Location: lib/rhashtable.c:1174
Inline: False
Direct callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff8158ded0-ffffffff8158df29: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815aaa60)
Location: lib/rhashtable.c:1174
Inline: False
Direct callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff815aaa60-ffffffff815aaab9: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b5680)
Location: lib/rhashtable.c:1174
Inline: False
Direct callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff815b5680-ffffffff815b56d9: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1174
Inline: False
Direct callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
**Symbols:**

```
ffffffff81cdaa9f-ffffffff81cdab20: __rht_bucket_nested.cold (STB_LOCAL)
ffffffff8161bab0-ffffffff8161bb3d: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1174
Inline: False
Direct callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
**Symbols:**

```
ffffffff81e9336f-ffffffff81e933f0: __rht_bucket_nested.cold (STB_LOCAL)
ffffffff816e9430-ffffffff816e94c9: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1178
Inline: False
Direct callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
**Symbols:**

```
ffffffff820784db-ffffffff8207855c: __rht_bucket_nested.cold (STB_LOCAL)
ffffffff817d9570-ffffffff817d9609: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1178
Inline: False
Direct callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
**Symbols:**

```
ffffffff820f8a37-ffffffff820f8abd: __rht_bucket_nested.cold (STB_LOCAL)
ffffffff81818780-ffffffff8181880c: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1178
Inline: False
Direct callers:
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
```
**Symbols:**

```
ffffffff821d6558-ffffffff821d65de: __rht_bucket_nested.cold (STB_LOCAL)
ffffffff8185da80-ffffffff8185db0c: __rht_bucket_nested (STB_GLOBAL)
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
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010635a10)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffff800010635a10-ffff800010635a6c: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07db92c)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
c07db92c-c07db98c: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db240)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
c0000000007db240-c0000000007db2cc: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe0004631d2)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffe0004631d2-ffffffe000463234: __rht_bucket_nested (STB_GLOBAL)
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
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522b70)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81522b70-ffffffff81522bc3: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81512e50)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff81512e50-ffffffff81512ea3: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ec00)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff8151ec00-ffffffff8151ec53: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rhash_lock_head **__rht_bucket_nested(const struct bucket_table *tbl, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815385a0)
Location: lib/rhashtable.c:1167
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:__rhashtable_walk_find_next
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - net/core/xdp.c:mem_xa_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
**Symbols:**

```
ffffffff815385a0-ffffffff815385f3: __rht_bucket_nested (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
