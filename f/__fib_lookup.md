# Function: <code>__fib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff817a67f0)
Location: net/ipv4/fib_rules.c:50
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff817a67f0-ffffffff817a6882: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff818144e0)
Location: net/ipv4/fib_rules.c:50
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff818144e0-ffffffff81814572: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81845c30)
Location: net/ipv4/fib_rules.c:50
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81845c30-ffffffff81845cd8: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81867790)
Location: net/ipv4/fib_rules.c:71
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff81867790-ffffffff81867838: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff818e78f0)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff818e78f0-ffffffff818e7998: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff8193e450)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff8193e450-ffffffff8193e4f9: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff8196e2f0)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8196e2f0-ffffffff8196e399: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff819d7aa0)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff819d7aa0-ffffffff819d7b49: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81a0e590)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a0e590-ffffffff81a0e639: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81aff480)
Location: net/ipv4/fib_rules.c:79
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81aff480-ffffffff81aff529: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81b0d4f0)
Location: net/ipv4/fib_rules.c:80
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81b0d4f0-ffffffff81b0d599: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81afb2c0)
Location: net/ipv4/fib_rules.c:80
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81afb2c0-ffffffff81afb369: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81bbc700)
Location: net/ipv4/fib_rules.c:80
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81bbc700-ffffffff81bbc7a9: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81d50cb0)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81d50cb0-ffffffff81d50d65: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81f1aaa0)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81f1aaa0-ffffffff81f1ab55: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81f7a720)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81f7a720-ffffffff81f7a7d5: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff82040e20)
Location: net/ipv4/fib_rules.c:81
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff82040e20-ffffffff82040ed5: __fib_lookup (STB_GLOBAL)
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
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffff800010cc8258)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffff800010cc8258-ffff800010cc8314: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (c0dd3748)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
c0dd3748-c0dd37f0: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (c000000000de5450)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
c000000000de5450-c000000000de5530: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffe00081c664)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffe00081c664-ffffffe00081c6ec: __fib_lookup (STB_GLOBAL)
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
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff819ae330)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff819ae330-ffffffff819ae3d9: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff8196a960)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff8196a960-ffffffff8196aa09: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81a18bd0)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a18bd0-ffffffff81a18c79: __fib_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __fib_lookup(struct net *net, struct flowi4 *flp, struct fib_result *res, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff81a23650)
Location: net/ipv4/fib_rules.c:78
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
**Symbols:**

```
ffffffff81a23650-ffffffff81a236f9: __fib_lookup (STB_GLOBAL)
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
