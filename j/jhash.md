# Function: <code>jhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b743)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/bpf/hashtab.c (ffffffff811777c5)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
```
```
In lib/rhashtable.c (ffffffff813ffbc0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff81780481)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad988)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
**Symbols:**

```
ffffffff813ffbc0-ffffffff813ffce5: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ed53)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811603f9)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff81186d90)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc7aa)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff814472c0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff817ed961)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181a96a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv6/calipso.c (ffffffff81870645)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
**Symbols:**

```
ffffffff813bb4b0-ffffffff813bb5d9: jhash (STB_LOCAL)
ffffffff814472c0-ffffffff814473e9: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3c3a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff8116ae59)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff81194120)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813d3bda)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff81465af0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e2af)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c22a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv6/calipso.c (ffffffff818a35b5)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff813d29c0-ffffffff813d2ae9: jhash (STB_LOCAL)
ffffffff81465af0-ffffffff81465c19: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0db9)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff8116dde9)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff8119b250)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813e696a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8146ab00)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81806310)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff8183e9ff)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/ipmr.c (ffffffff81867f50)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186fcba)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv6/calipso.c (ffffffff818c9b7f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbcd7)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff813e5540-ffffffff813e5669: jhash (STB_LOCAL)
ffffffff8146ab00-ffffffff8146ac29: jhash (STB_LOCAL)
ffffffff81806310-ffffffff81806439: jhash (STB_LOCAL)
ffffffff81867f50-ffffffff81868079: jhash (STB_LOCAL)
ffffffff818cbcd7-ffffffff818cbe0c: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7608)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff8117aea6)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff811aaa90)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In ipc/util.c (ffffffff813a6a30)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8140daea)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff81496de0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/sched/act_api.c (ffffffff818814d0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81885040)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff818be24f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/ipmr.c (ffffffff818e7fc0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f065b)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv6/route.c (ffffffff8191b74a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/calipso.c (ffffffff8194d25f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950a7c)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff813a6a30-ffffffff813a6b5f: jhash (STB_LOCAL)
ffffffff8140c720-ffffffff8140c84f: jhash (STB_LOCAL)
ffffffff81496de0-ffffffff81496f0f: jhash (STB_LOCAL)
ffffffff818814d0-ffffffff818815ff: jhash (STB_LOCAL)
ffffffff81885040-ffffffff8188516f: jhash (STB_LOCAL)
ffffffff818e7fc0-ffffffff818e80ef: jhash (STB_LOCAL)
ffffffff81950a7c-ffffffff81950bb7: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ae16c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff8118a009)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff811c1ed0)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811d06e9)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:__sock_hash_lookup_elem
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_get_next_key
```
```
In ipc/util.c (ffffffff813d5d40)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e7b7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff814cc040)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff81913e6f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81946f77)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv6/route.c (ffffffff8197346a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819a5a07)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff813d5d40-ffffffff813d5e6a: jhash (STB_LOCAL)
ffffffff8143e070-ffffffff8143e19a: jhash (STB_LOCAL)
ffffffff814cc040-ffffffff814cc16a: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b72a3)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff81197919)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff811d3833)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff813f03a0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b687)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff814e0620)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff818f3028)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/sched/cls_api.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819425cf)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff819688f0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978ad7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a90ba)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819dcb77)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff813f03a0-ffffffff813f0521: jhash (STB_LOCAL)
ffffffff8145aee0-ffffffff8145b061: jhash (STB_LOCAL)
ffffffff814e0620-ffffffff814e07a1: jhash (STB_LOCAL)
ffffffff819688f0-ffffffff81968a71: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc62a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811a4ff9)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e8520)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff8141c6d0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488bd7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8150c5c0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff81945502)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/sched/cls_api.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6bbf)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e25f7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a15eea)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a4b7ac)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff8141c6d0-ffffffff8141c841: jhash (STB_LOCAL)
ffffffff8150c5c0-ffffffff8150c731: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c337a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811b0829)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f4c80)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff81436520)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2a87)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8152a410)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff8197a522)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819dd88f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a195e7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4cb2a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a8237c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff81436520-ffffffff81436691: jhash (STB_LOCAL)
ffffffff8152a410-ffffffff8152a581: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6020)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff811c8cd0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff81216990)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/offload.c (ffffffff812289a0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In ipc/util.c (ffffffff814862c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff814be5e0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff814eae60)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff814fc6f0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8158dd50)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81a35400)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81a4dc90)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81a76100)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81aca920)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81af4e60)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81affc20)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81b05d70)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b09f20)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d6c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81b72f40)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81b7c360)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80800)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff810c6020-ffffffff810c6173: jhash (STB_LOCAL)
ffffffff811c8cd0-ffffffff811c8e40: jhash.constprop.0 (STB_LOCAL)
ffffffff81216990-ffffffff81216b01: jhash (STB_LOCAL)
ffffffff812289a0-ffffffff81228b17: jhash (STB_LOCAL)
ffffffff814862c0-ffffffff81486437: jhash (STB_LOCAL)
ffffffff814be5e0-ffffffff814be715: jhash.constprop.0 (STB_LOCAL)
ffffffff814eae60-ffffffff814eafd7: jhash (STB_LOCAL)
ffffffff814fc6f0-ffffffff814fc861: jhash (STB_LOCAL)
ffffffff8158dd50-ffffffff8158dec1: jhash (STB_LOCAL)
ffffffff81a35400-ffffffff81a35577: jhash (STB_LOCAL)
ffffffff81a4dc90-ffffffff81a4de00: jhash.constprop.0 (STB_LOCAL)
ffffffff81a76100-ffffffff81a76277: jhash (STB_LOCAL)
ffffffff81aca920-ffffffff81aca9e6: jhash.constprop.0 (STB_LOCAL)
ffffffff81af4e60-ffffffff81af4fd7: jhash (STB_LOCAL)
ffffffff81affc20-ffffffff81affd97: jhash (STB_LOCAL)
ffffffff81b05d70-ffffffff81b05ee7: jhash (STB_LOCAL)
ffffffff81b09f20-ffffffff81b0a096: jhash.constprop.0 (STB_LOCAL)
ffffffff81b0d6c0-ffffffff81b0d837: jhash (STB_LOCAL)
ffffffff81b72f40-ffffffff81b730b7: jhash (STB_LOCAL)
ffffffff81b7c360-ffffffff81b7c4d6: jhash.constprop.0 (STB_LOCAL)
ffffffff81b80800-ffffffff81b80977: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0ff0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff811c6390)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff81218ae0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/offload.c (ffffffff812304e0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In ipc/util.c (ffffffff814a38c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dc000)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff81508260)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff81519960)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff815aa8e0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81a37790)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81a53c80)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81a7ee70)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad68a0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81b01c60)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81b0dca0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81b13f60)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b182e0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1b8d0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81b81cb0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81b8b3a0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90070)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff810c0ff0-ffffffff810c1143: jhash (STB_LOCAL)
ffffffff811c6390-ffffffff811c6500: jhash.constprop.0 (STB_LOCAL)
ffffffff81218ae0-ffffffff81218c51: jhash (STB_LOCAL)
ffffffff812304e0-ffffffff81230657: jhash (STB_LOCAL)
ffffffff814a38c0-ffffffff814a3a37: jhash (STB_LOCAL)
ffffffff814dc000-ffffffff814dc135: jhash.constprop.0 (STB_LOCAL)
ffffffff81508260-ffffffff815083d7: jhash (STB_LOCAL)
ffffffff81519960-ffffffff81519ad1: jhash (STB_LOCAL)
ffffffff815aa8e0-ffffffff815aaa51: jhash (STB_LOCAL)
ffffffff81a37790-ffffffff81a37907: jhash (STB_LOCAL)
ffffffff81a53c80-ffffffff81a53df0: jhash.constprop.0 (STB_LOCAL)
ffffffff81a7ee70-ffffffff81a7efe7: jhash (STB_LOCAL)
ffffffff81ad68a0-ffffffff81ad6966: jhash.constprop.0 (STB_LOCAL)
ffffffff81b01c60-ffffffff81b01dd7: jhash (STB_LOCAL)
ffffffff81b0dca0-ffffffff81b0de17: jhash (STB_LOCAL)
ffffffff81b13f60-ffffffff81b140d7: jhash (STB_LOCAL)
ffffffff81b182e0-ffffffff81b18456: jhash.constprop.0 (STB_LOCAL)
ffffffff81b1b8d0-ffffffff81b1ba47: jhash (STB_LOCAL)
ffffffff81b81cb0-ffffffff81b81e27: jhash (STB_LOCAL)
ffffffff81b8b3a0-ffffffff81b8b516: jhash.constprop.0 (STB_LOCAL)
ffffffff81b90070-ffffffff81b901e7: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c29f0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff811c73d0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff8121c3c0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/offload.c (ffffffff81234690)
Location: include/linux/jhash.h:70
Inline: False
```
```
In ipc/util.c (ffffffff814a98c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e2960)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff8150edd0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff81520270)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff815b5500)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81a1e8f0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81a4f780)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81a67cd0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1920)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed570)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81afbaa0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81b01da0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06030)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b095c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81b708d0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81b7a1f0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f2b0)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff810c29f0-ffffffff810c2b3a: jhash (STB_LOCAL)
ffffffff811c73d0-ffffffff811c7543: jhash.constprop.0 (STB_LOCAL)
ffffffff8121c3c0-ffffffff8121c534: jhash (STB_LOCAL)
ffffffff81234690-ffffffff8123480d: jhash (STB_LOCAL)
ffffffff814a98c0-ffffffff814a9a3d: jhash (STB_LOCAL)
ffffffff814e2960-ffffffff814e2a78: jhash.constprop.0 (STB_LOCAL)
ffffffff8150edd0-ffffffff8150ef4d: jhash (STB_LOCAL)
ffffffff81520270-ffffffff815203e4: jhash (STB_LOCAL)
ffffffff815b5500-ffffffff815b5674: jhash (STB_LOCAL)
ffffffff81a1e8f0-ffffffff81a1ea6d: jhash (STB_LOCAL)
ffffffff81a4f780-ffffffff81a4f8f3: jhash.constprop.0 (STB_LOCAL)
ffffffff81a67cd0-ffffffff81a67e4d: jhash (STB_LOCAL)
ffffffff81ac1920-ffffffff81ac19dc: jhash.constprop.0 (STB_LOCAL)
ffffffff81aed570-ffffffff81aed6ed: jhash (STB_LOCAL)
ffffffff81afbaa0-ffffffff81afbc1d: jhash (STB_LOCAL)
ffffffff81b01da0-ffffffff81b01f1d: jhash (STB_LOCAL)
ffffffff81b06030-ffffffff81b061ac: jhash.constprop.0 (STB_LOCAL)
ffffffff81b095c0-ffffffff81b0973d: jhash (STB_LOCAL)
ffffffff81b708d0-ffffffff81b70a4d: jhash (STB_LOCAL)
ffffffff81b7a1f0-ffffffff81b7a36c: jhash.constprop.0 (STB_LOCAL)
ffffffff81b7f2b0-ffffffff81b7f42d: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810d5530)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff811f2ae0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff81253290)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/offload.c (ffffffff8126e7d0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In ipc/util.c (ffffffff81501c50)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153bb20)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff8156c990)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff8157e410)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8161b930)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81ad2990)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81b083c0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81b21240)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7f650)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81bad930)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81bbcf40)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc3be0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc8d20)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc540)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ioam6.c (ffffffff81c38930)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ac30)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81c44eb0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4ab10)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff810d5530-ffffffff810d567a: jhash (STB_LOCAL)
ffffffff811f2ae0-ffffffff811f2c53: jhash.constprop.0 (STB_LOCAL)
ffffffff81253290-ffffffff81253404: jhash (STB_LOCAL)
ffffffff8126e7d0-ffffffff8126e94d: jhash (STB_LOCAL)
ffffffff81501c50-ffffffff81501dcd: jhash (STB_LOCAL)
ffffffff8153bb20-ffffffff8153bc38: jhash.constprop.0 (STB_LOCAL)
ffffffff8156c990-ffffffff8156cb0d: jhash (STB_LOCAL)
ffffffff8157e410-ffffffff8157e584: jhash (STB_LOCAL)
ffffffff8161b930-ffffffff8161baa4: jhash (STB_LOCAL)
ffffffff81ad2990-ffffffff81ad2b0d: jhash (STB_LOCAL)
ffffffff81b083c0-ffffffff81b08533: jhash.constprop.0 (STB_LOCAL)
ffffffff81b21240-ffffffff81b213bd: jhash (STB_LOCAL)
ffffffff81b7f650-ffffffff81b7f70c: jhash.constprop.0 (STB_LOCAL)
ffffffff81bad930-ffffffff81badaad: jhash (STB_LOCAL)
ffffffff81bbcf40-ffffffff81bbd0bd: jhash (STB_LOCAL)
ffffffff81bc3be0-ffffffff81bc3d5d: jhash (STB_LOCAL)
ffffffff81bc8d20-ffffffff81bc8e9c: jhash.constprop.0 (STB_LOCAL)
ffffffff81bcc540-ffffffff81bcc6bd: jhash (STB_LOCAL)
ffffffff81c38930-ffffffff81c38aad: jhash (STB_LOCAL)
ffffffff81c3ac30-ffffffff81c3adad: jhash (STB_LOCAL)
ffffffff81c44eb0-ffffffff81c4502c: jhash.constprop.0 (STB_LOCAL)
ffffffff81c4ab10-ffffffff81c4ac8d: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810ee390)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff8122c090)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff8129b610)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a4650)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In kernel/bpf/btf.c (ffffffff812aaca0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812bd700)
Location: include/linux/jhash.h:70
Inline: False
```
```
In mm/kfence/core.c (ffffffff813ae140)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In ipc/util.c (ffffffff815930b0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d3380)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff81608d80)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff8161cb70)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff816e91d0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81c50450)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81c8e320)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81ca9610)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f870)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40990)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81d515f0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81d58ba0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5e4d0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62220)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ioam6.c (ffffffff81dd65a0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81dd8b60)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81de3f30)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea3a0)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff810ee390-ffffffff810ee50b: jhash (STB_LOCAL)
ffffffff8122c090-ffffffff8122c20a: jhash.constprop.0 (STB_LOCAL)
ffffffff8129b610-ffffffff8129b78b: jhash (STB_LOCAL)
ffffffff812a4650-ffffffff812a47cb: jhash (STB_LOCAL)
ffffffff812aaca0-ffffffff812aae1a: jhash.constprop.0 (STB_LOCAL)
ffffffff812bd700-ffffffff812bd87b: jhash (STB_LOCAL)
ffffffff813ae140-ffffffff813ae2bb: jhash (STB_LOCAL)
ffffffff815930b0-ffffffff8159322b: jhash (STB_LOCAL)
ffffffff815d3380-ffffffff815d34aa: jhash.constprop.0 (STB_LOCAL)
ffffffff81608d80-ffffffff81608efb: jhash (STB_LOCAL)
ffffffff8161cb70-ffffffff8161cceb: jhash (STB_LOCAL)
ffffffff816e91d0-ffffffff816e934b: jhash (STB_LOCAL)
ffffffff81c50450-ffffffff81c505cb: jhash (STB_LOCAL)
ffffffff81c8e320-ffffffff81c8e49a: jhash.constprop.0 (STB_LOCAL)
ffffffff81ca9610-ffffffff81ca978b: jhash (STB_LOCAL)
ffffffff81d0f870-ffffffff81d0f924: jhash.constprop.0 (STB_LOCAL)
ffffffff81d40990-ffffffff81d40b0b: jhash (STB_LOCAL)
ffffffff81d515f0-ffffffff81d5176b: jhash (STB_LOCAL)
ffffffff81d58ba0-ffffffff81d58d1b: jhash (STB_LOCAL)
ffffffff81d5e4d0-ffffffff81d5e64a: jhash.constprop.0 (STB_LOCAL)
ffffffff81d62220-ffffffff81d6239b: jhash (STB_LOCAL)
ffffffff81dd65a0-ffffffff81dd671b: jhash (STB_LOCAL)
ffffffff81dd8b60-ffffffff81dd8cdb: jhash (STB_LOCAL)
ffffffff81de3f30-ffffffff81de40aa: jhash.constprop.0 (STB_LOCAL)
ffffffff81dea3a0-ffffffff81dea51b: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8110f8b0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff81277bb0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/hashtab.c (ffffffff812f7c70)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bloom_filter.c (ffffffff81302320)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In kernel/bpf/btf.c (ffffffff8130a5a0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff81320bc0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134ca00)
Location: include/linux/jhash.h:70
Inline: False
```
```
In mm/kfence/core.c (ffffffff8142e570)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In ipc/util.c (ffffffff8163bba0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff816813c0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff816ba6b0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff816cfe20)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff817d92e0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (ffffffff81e05830)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81e496c0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (ffffffff81e66560)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5450)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81f096b0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (ffffffff81f1b4b0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81f22f90)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f28be0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2ccd0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ioam6.c (ffffffff81fa7e80)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81faa600)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff81fb6630)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbdca0)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff8110f8b0-ffffffff8110fa2b: jhash (STB_LOCAL)
ffffffff81277bb0-ffffffff81277d2a: jhash.constprop.0 (STB_LOCAL)
ffffffff812f7c70-ffffffff812f7deb: jhash (STB_LOCAL)
ffffffff81302320-ffffffff8130249b: jhash (STB_LOCAL)
ffffffff8130a5a0-ffffffff8130a71a: jhash.constprop.0 (STB_LOCAL)
ffffffff81320bc0-ffffffff81320d3b: jhash (STB_LOCAL)
ffffffff8134ca00-ffffffff8134cb7b: jhash (STB_LOCAL)
ffffffff8142e570-ffffffff8142e6eb: jhash (STB_LOCAL)
ffffffff8163bba0-ffffffff8163bd1b: jhash (STB_LOCAL)
ffffffff816813c0-ffffffff816814ea: jhash.constprop.0 (STB_LOCAL)
ffffffff816ba6b0-ffffffff816ba82b: jhash (STB_LOCAL)
ffffffff816cfe20-ffffffff816cff9b: jhash (STB_LOCAL)
ffffffff817d92e0-ffffffff817d945b: jhash (STB_LOCAL)
ffffffff81e05830-ffffffff81e059ab: jhash (STB_LOCAL)
ffffffff81e496c0-ffffffff81e4983a: jhash.constprop.0 (STB_LOCAL)
ffffffff81e66560-ffffffff81e666db: jhash (STB_LOCAL)
ffffffff81ed5450-ffffffff81ed5504: jhash.constprop.0 (STB_LOCAL)
ffffffff81f096b0-ffffffff81f0982b: jhash (STB_LOCAL)
ffffffff81f1b4b0-ffffffff81f1b62b: jhash (STB_LOCAL)
ffffffff81f22f90-ffffffff81f2310b: jhash (STB_LOCAL)
ffffffff81f28be0-ffffffff81f28d5a: jhash.constprop.0 (STB_LOCAL)
ffffffff81f2ccd0-ffffffff81f2ce4b: jhash (STB_LOCAL)
ffffffff81fa7e80-ffffffff81fa7ffb: jhash (STB_LOCAL)
ffffffff81faa600-ffffffff81faa77b: jhash (STB_LOCAL)
ffffffff81fb6630-ffffffff81fb67aa: jhash.constprop.0 (STB_LOCAL)
ffffffff81fbdca0-ffffffff81fbde1b: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8111bd50)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff8128f5f0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_events_user.c (ffffffff812c4ab0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/trace_events_user.c:find_user_event
```
```
In kernel/bpf/hashtab.c (ffffffff81325b50)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff81330eb0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:hash
```
```
In kernel/bpf/btf.c (ffffffff81339e60)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In mm/kfence/core.c (ffffffff81463cd0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff816b9570)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff816f3030)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff81708a40)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff818184f0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81ea4d80)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34100)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff81f691c0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff81f82ad0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f88750)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ioam6.c (ffffffff82008810)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff82016d40)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/handshake/request.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff8111bd50-ffffffff8111bea8: jhash (STB_LOCAL)
ffffffff8128f5f0-ffffffff8128f76e: jhash.constprop.0 (STB_LOCAL)
ffffffff812c4ab0-ffffffff812c4c2e: jhash.constprop.0 (STB_LOCAL)
ffffffff81325b50-ffffffff81325cce: jhash (STB_LOCAL)
ffffffff81330eb0-ffffffff8133102e: jhash (STB_LOCAL)
ffffffff81339e60-ffffffff81339fde: jhash.constprop.0 (STB_LOCAL)
ffffffff81463cd0-ffffffff81463e28: jhash (STB_LOCAL)
ffffffff816b9570-ffffffff816b969a: jhash.constprop.0 (STB_LOCAL)
ffffffff816f3030-ffffffff816f31ae: jhash (STB_LOCAL)
ffffffff81708a40-ffffffff81708bbe: jhash (STB_LOCAL)
ffffffff818184f0-ffffffff8181866e: jhash (STB_LOCAL)
ffffffff81ea4d80-ffffffff81ea4efe: jhash.constprop.0 (STB_LOCAL)
ffffffff81f34100-ffffffff81f341b4: jhash.constprop.0 (STB_LOCAL)
ffffffff81f691c0-ffffffff81f6933e: jhash (STB_LOCAL)
ffffffff81f82ad0-ffffffff81f82c4e: jhash (STB_LOCAL)
ffffffff81f88750-ffffffff81f888ce: jhash.constprop.0 (STB_LOCAL)
ffffffff82008810-ffffffff8200898e: jhash (STB_LOCAL)
ffffffff82016d40-ffffffff82016ebe: jhash.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81125870)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/trace/tracing_map.c (ffffffff812aab50)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_events_user.c (ffffffff812e12d0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - kernel/trace/trace_events_user.c:find_user_event
```
```
In kernel/bpf/hashtab.c (ffffffff8134a090)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_hash
```
```
In kernel/bpf/bloom_filter.c (ffffffff81355450)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:hash
```
```
In kernel/bpf/btf.c (ffffffff8135ff90)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In mm/kfence/core.c (ffffffff81493070)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f6000)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In security/apparmor/apparmorfs.c (ffffffff8172fdf0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In security/apparmor/policy_unpack.c (ffffffff817464d0)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8185d7f0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/sock_map.c (ffffffff81f677e0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa280)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_update_congestion_control
```
```
In net/ipv4/inet_fragment.c (ffffffff8202f840)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/ipmr_base.c (ffffffff82049150)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8204fe10)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/ioam6.c (ffffffff820d7730)
Location: include/linux/jhash.h:70
Inline: False
Direct callers:
  - net/ipv6/ioam6.c:ioam6_namespace
  - net/ipv6/ioam6.c:ioam6_genl_ns_set_schema
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/calipso.c (ffffffff820e5ce0)
Location: include/linux/jhash.h:70
Inline: True
Direct callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/handshake/request.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
**Symbols:**

```
ffffffff81125870-ffffffff811259c8: jhash (STB_LOCAL)
ffffffff812aab50-ffffffff812aacce: jhash.constprop.0 (STB_LOCAL)
ffffffff812e12d0-ffffffff812e144e: jhash.constprop.0 (STB_LOCAL)
ffffffff8134a090-ffffffff8134a20e: jhash (STB_LOCAL)
ffffffff81355450-ffffffff813555ce: jhash (STB_LOCAL)
ffffffff8135ff90-ffffffff8136010e: jhash.constprop.0 (STB_LOCAL)
ffffffff81493070-ffffffff814931c8: jhash (STB_LOCAL)
ffffffff816f6000-ffffffff816f612a: jhash.constprop.0 (STB_LOCAL)
ffffffff8172fdf0-ffffffff8172ff6e: jhash (STB_LOCAL)
ffffffff817464d0-ffffffff8174664e: jhash (STB_LOCAL)
ffffffff8185d7f0-ffffffff8185d96e: jhash (STB_LOCAL)
ffffffff81f677e0-ffffffff81f6795e: jhash.constprop.0 (STB_LOCAL)
ffffffff81ffa280-ffffffff81ffa334: jhash.constprop.0 (STB_LOCAL)
ffffffff8202f840-ffffffff8202f9be: jhash (STB_LOCAL)
ffffffff82049150-ffffffff820492ce: jhash (STB_LOCAL)
ffffffff8204fe10-ffffffff8204ff8e: jhash.constprop.0 (STB_LOCAL)
ffffffff820d7730-ffffffff820d78ae: jhash (STB_LOCAL)
ffffffff820e5ce0-ffffffff820e5e5e: jhash.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121108)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffff80001022e94c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
```
```
In kernel/bpf/hashtab.c (ffff800010278f50)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff80001059875c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffff800010635850)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffff800010c2180c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffff800010c90c58)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd52c0)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/route.c (ffff800010d0fa60)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffff800010d4e660)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffff800010635850-ffff800010635a0c: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375048)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/bpf/hashtab.c (c04ab434)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (c06d8d64)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (c07499d4)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (c07db6dc)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (c0d38ec8)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (c0d9f9f4)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (c0ddf28c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (c0e170d4)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (c0e4ef84)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
c06d8d64-c06d8edc: jhash (STB_LOCAL)
c07db6dc-c07db854: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a688)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (c0000000002b7f00)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
```
```
In kernel/bpf/hashtab.c (c000000000321d68)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (c00000000070f64c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (c0000000007db010)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (c000000000d13cbc)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (c000000000da025c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4894)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/route.c (c000000000e3d264)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (c000000000e84e74)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
c0000000007db010-c0000000007db23c: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da04e)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/bpf/hashtab.c (ffffffe0001b1062)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e508a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffe000462fa2)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffe00079a610)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0ac0)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000825f56)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: False
```
```
In net/ipv6/route.c (ffffffe000857478)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffe000886d6e)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffe000462fa2-ffffffe0004631d2: jhash (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd6ea)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811a8e49)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ed2a0)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff8142eb00)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b067)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff815229f0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff8191a392)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d6ff)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8c77)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ec1ba)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a21a0c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff8142eb00-ffffffff8142ec71: jhash (STB_LOCAL)
ffffffff815229f0-ffffffff81522b61: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abf1a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff8119bdc9)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e0030)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff8141f580)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148ba87)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff81512cd0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff81770552)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff818d4142)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819371bf)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975a67)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a8f7a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819de7cc)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff8141f580-ffffffff8141f6f1: jhash (STB_LOCAL)
ffffffff81512cd0-ffffffff81512e41: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bcc4a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811a6c19)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811eb070)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff8142aca0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81497107)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff8151ea80)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff8196b522)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819e7ecf)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a236f7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a56c3a)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a8c48c)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff8142aca0-ffffffff8142ae11: jhash (STB_LOCAL)
ffffffff8151ea80-ffffffff8151ebf1: jhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 jhash(const void *key, u32 length, u32 initval);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4fca)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/trace/tracing_map.c (ffffffff811b49b9)
Location: include/linux/jhash.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f9470)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In ipc/util.c (ffffffff81441b60)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af1d7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:strhash
```
```
In lib/rhashtable.c (ffffffff81538350)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/core/sock_map.c (ffffffff8198d992)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1c3f)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2ead7)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a62cea)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_exception_hash
  - net/ipv6/route.c:rt6_exception_hash
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a9921d)
Location: include/linux/jhash.h:70
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/jhash.h:70
Inline: True
```
**Symbols:**

```
ffffffff81441b60-ffffffff81441cd1: jhash (STB_LOCAL)
ffffffff81538350-ffffffff815384c1: jhash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
