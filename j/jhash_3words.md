# Function: <code>jhash_3words</code>

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
In net/ipv4/route.c (ffffffff81754dc7)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81759297)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff81761f40)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81788ca0)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff817e337e)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff817eda2f)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81800706)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801cae)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff817c0f47)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5637)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce24c)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff817f65fc)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff8185190d)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8185c273)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81871e26)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187301d)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff817f0547)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5137)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fdfec)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8182755c)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff818836cd)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8188e183)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff818a6406)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a763d)
Location: include/linux/jhash.h:160
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8180ed77)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff818155d8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e410)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81848cd0)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff818a995d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff818b4827)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff818cce56)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cdf3d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8188e31f)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff8189478e)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipqhashfn
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d2ee)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff818c86fe)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff8192c30d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/reassembly.c (ffffffff8193757f)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
```
```
In net/ipv6/output_core.c (ffffffff81951c46)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952d2d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff818e203f)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1948)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8191cca8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/ipv6/udp.c (ffffffff8198477d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff819ab1d5)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac2bd)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8190eedf)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f528)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8194bde6)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bf45)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff819bae69)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/output_core.c (ffffffff819e1cf5)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e9d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (ffffffff81981e98)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819b0551)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5425)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff81a28d05)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51c2d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffff81999438)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b86e8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819e721b)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c455)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff81a5f84c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8882d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In security/selinux/ss/context.c (ffffffff814d0235)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a6c315)
Location: include/linux/jhash.h:159
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa31a8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81ad2ad7)
Location: include/linux/jhash.h:159
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f685)
Location: include/linux/jhash.h:159
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b5931d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83e6d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In security/selinux/ss/context.c (ffffffff814ed765)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a74cb5)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad6d8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81addc38)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d975)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b6794d)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b936cd)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In security/selinux/ss/context.c (ffffffff814f44e5)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81a5d865)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a987a8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81ac8c28)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b1c5)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b55b2d)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b827dd)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81bbccbc)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/selinux/ss/context.c (ffffffff8154ee95)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81b16775)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53c88)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81b874b8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce095)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b5ed)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e8ad)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81c8cb1c)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/selinux/ss/context.c (ffffffff815e8011)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81c9de65)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1848)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81d182e8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d64165)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7d0d)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def1dd)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81e361cc)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/selinux/ss/context.c (ffffffff81697751)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81e5a555)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea29f8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81edebf8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2eee5)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87d3d)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc328d)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8200f19c)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/selinux/ss/context.c (ffffffff816cfc51)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81eb5e05)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01218)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81f3e038)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f425)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fea846)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024146)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8208bd8c)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/selinux/ss/policydb.c (ffffffff816fc388)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:role_trans_hash
```
```
In security/selinux/ss/context.c (ffffffff8170c271)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/sched/cls_api.c (ffffffff81f78b15)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc54c8)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff82004168)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_ehashfn
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d015)
Location: include/linux/jhash.h:161
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b8766)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f32b6)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8216224c)
Location: include/linux/jhash.h:161
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/sched/cls_api.c (ffff800010c46138)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69b28)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffff800010c99b54)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda654)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffff800010d23d14)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55444)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (c0d55fcc)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (c0d78e10)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (c0daae84)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (c0de226c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (c0e297f8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c0e559fc)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (c000000000d40b50)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (c000000000d6eacc)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (c000000000dae6ac)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (c000000000df8df8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (c000000000e55cb4)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e25c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffe0007b3018)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf972)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffe0007f9662)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b2de)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffe00086694e)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cbee)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffff819392a8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958558)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff8198708b)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbae5)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff819feedc)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a27ebd)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffff818f2da8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912048)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff81940b4b)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff819788d5)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff819bbc9c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c7d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffff8198a438)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2d28)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819f185b)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26565)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff81a6995c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93a6d)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/sched/cls_api.c (ffffffff819ab7a7)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc7f8)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/udp.c (ffffffff819fcb52)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31a15)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/udp.c (ffffffff81a75f3c)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fbbd)
Location: include/linux/jhash.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
</details>
</li>
</ul>

## Differences
