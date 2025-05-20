# Function: <code>fib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81754070)
Location: include/net/ip_fib.h:261
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
Direct callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff8179ab1a)
Location: include/net/ip_fib.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d45b)
Location: include/net/ip_fib.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81754070-ffffffff817540fa: fib_lookup.constprop.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817c2901)
Location: include/net/ip_fib.h:262
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
Direct callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff818089ba)
Location: include/net/ip_fib.h:262
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8180ae55)
Location: include/net/ip_fib.h:262
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff817c0120-ffffffff817c01aa: fib_lookup.constprop.43 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff817f0fa2)
Location: include/net/ip_fib.h:304
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81839a86)
Location: include/net/ip_fib.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8183bf63)
Location: include/net/ip_fib.h:304
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/route.c (ffffffff818126e7)
Location: include/net/ip_fib.h:338
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff8185affc)
Location: include/net/ip_fib.h:338
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c786)
Location: include/net/ip_fib.h:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81891d07)
Location: include/net/ip_fib.h:306
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
Direct callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff818daf8c)
Location: include/net/ip_fib.h:306
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc676)
Location: include/net/ip_fib.h:306
Inline: True
```
**Symbols:**

```
ffffffff8189345c-ffffffff818934d9: fib_lookup.constprop.48 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b4339)
Location: include/net/ip_fib.h:314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff818e5bb0)
Location: include/net/ip_fib.h:314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff8193129e)
Location: include/net/ip_fib.h:314
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8193326f)
Location: include/net/ip_fib.h:314
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
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
In net/core/filter.c (ffffffff818d9ae9)
Location: include/net/ip_fib.h:325
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81912ac2)
Location: include/net/ip_fib.h:325
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81960b8e)
Location: include/net/ip_fib.h:325
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81963b8c)
Location: include/net/ip_fib.h:325
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/core/filter.c (ffffffff8192a402)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81975278)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff819c566a)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819c7b85)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff8195c792)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819abc91)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc20a)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe735)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81a2df81)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a95cf7)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea40a)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed00c)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81a2fea6)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a9fd73)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81af726a)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81af9c64)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81a16fff)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81a8acb3)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae29b0)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae52af)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81ac926f)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81b45bad)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2240)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba4f7f)
Location: include/net/ip_fib.h:364
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81c462a6)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81cd2986)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3496a)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37960)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81dfa783)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81e92c56)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81efce68)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f004c0)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81e6e1bc)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81ef13f6)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c8a8)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5ff40)
Location: include/net/ip_fib.h:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff81f2da89)
Location: include/net/ip_fib.h:368
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff81fb5546)
Location: include/net/ip_fib.h:368
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff82022e5f)
Location: include/net/ip_fib.h:368
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff82026513)
Location: include/net/ip_fib.h:368
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffff800010bfe584)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffff800010c5bdc8)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffff800010cb45fc)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6df4)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (c0d18d08)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c0d6b434)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (c0dbfb54)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c0dc30d0)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
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
In net/core/filter.c (c000000000ce61f8)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (c000000000d5df78)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (c000000000dcb610)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c000000000dcf060)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffe0007805de)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffe0007c4f1a)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c2ce)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffe00080df94)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff818fc762)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff8194bb01)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bfaa)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8199e4d5)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff818b6592)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819055f1)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81955a6a)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81957f95)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff8194d792)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819b62d1)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0684a)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08d75)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
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
In net/core/filter.c (ffffffff8196f157)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
```
In net/ipv4/route.c (ffffffff819bfad1)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10eca)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a134eb)
Location: include/net/ip_fib.h:345
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
</details>
</li>
</ul>

## Differences
