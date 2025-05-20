# Function: <code>fib_table_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8179ebc0)
Location: net/ipv4/fib_trie.c:1269
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8179ebc0-ffffffff8179ef46: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180c640)
Location: net/ipv4/fib_trie.c:1267
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8180c640-ffffffff8180c99d: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183d8c0)
Location: net/ipv4/fib_trie.c:1377
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8183d8c0-ffffffff8183dc1a: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8185f0d0)
Location: net/ipv4/fib_trie.c:1298
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
**Symbols:**

```
ffffffff8185f0d0-ffffffff8185f41f: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818df130)
Location: net/ipv4/fib_trie.c:1296
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
**Symbols:**

```
ffffffff818df130-ffffffff818df48f: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81937420)
Location: net/ipv4/fib_trie.c:1316
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81937420-ffffffff8193788c: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81966e10)
Location: net/ipv4/fib_trie.c:1316
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81966e10-ffffffff8196727c: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819ccee0)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff819ccee0-ffffffff819cd470: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a03a30)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a03a30-ffffffff81a03fbe: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af3920)
Location: net/ipv4/fib_trie.c:1395
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81af3920-ffffffff81af4026: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b00850)
Location: net/ipv4/fib_trie.c:1395
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81b00850-ffffffff81b00e2a: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aebee0)
Location: net/ipv4/fib_trie.c:1432
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81aebee0-ffffffff81aec4c7: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:1436
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81d3d797-ffffffff81d3d99b: fib_table_lookup.cold (STB_LOCAL)
ffffffff81bac100-ffffffff81bac807: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:1442
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81f0a04b-ffffffff81f0a28a: fib_table_lookup.cold (STB_LOCAL)
ffffffff81d3ef60-ffffffff81d3f6af: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:1444
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff820b1915-ffffffff820b1b54: fib_table_lookup.cold (STB_LOCAL)
ffffffff81f07b50-ffffffff81f082a4: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:1444
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff82132b75-ffffffff82132d8d: fib_table_lookup.cold (STB_LOCAL)
ffffffff81f67630-ffffffff81f67dbc: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:1445
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff82214533-ffffffff8221474b: fib_table_lookup.cold (STB_LOCAL)
ffffffff8202dc10-ffffffff8202e39e: fib_table_lookup (STB_GLOBAL)
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
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbc4f0)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffff800010cbc4f0-ffff800010cbcb80: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc7d60)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
c0dc7d60-c0dc8494: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd6180)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
c000000000dd6180-c000000000dd69a0: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe0008129bc)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:nl_fib_lookup
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:__inet_dev_addr_type
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffe0008129bc-ffffffe000812f68: fib_table_lookup (STB_GLOBAL)
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
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a37d0)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff819a37d0-ffffffff819a3d5e: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195d290)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff8195d290-ffffffff8195d81e: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0e070)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a0e070-ffffffff81a0e5fe: fib_table_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_table_lookup(struct fib_table *tb, const struct flowi4 *flp, struct fib_result *res, int fib_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a18880)
Location: net/ipv4/fib_trie.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a18880-ffffffff81a18e4a: fib_table_lookup (STB_GLOBAL)
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
