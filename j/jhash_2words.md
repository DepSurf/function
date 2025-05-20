# Function: <code>jhash_2words</code>

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
In net/ipv4/route.c (ffffffff81755971)
Location: include/linux/jhash.h:165
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178e1d8)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b21ea)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff817c1b21)
Location: include/linux/jhash.h:165
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fb7d5)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81820067)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff817f2111)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/icmp.c (ffffffff8182c6a2)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818518c6)
Location: include/linux/jhash.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81874748)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f4caf)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194b623)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197dee3)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff81973da1)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e740a)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff819aa7c1)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1e3fa)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In security/selinux/ss/context.c (ffffffff814d0286)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81a94add)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b103fe)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In security/selinux/ss/context.c (ffffffff814ed7b6)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81a9eadd)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1e6ee)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In security/selinux/ss/context.c (ffffffff814f4536)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81a89a3e)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c3e5)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In security/selinux/ss/context.c (ffffffff8154eee6)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81b446f3)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcf427)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81c0a9ee)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In security/selinux/ss/context.c (ffffffff815e8062)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81cd13ac)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6543f)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81da57a1)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In security/selinux/ss/context.c (ffffffff816977a2)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81e918dc)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f303a0)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81f74ce1)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In security/selinux/ss/context.c (ffffffff816cfca2)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81ef0091)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8ec82)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff81fd4d81)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In security/selinux/ss/context.c (ffffffff8170c2c2)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - security/selinux/ss/context.c:context_compute_hash
```
```
In net/ipv4/route.c (ffffffff81fb41e1)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205c992)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
```
In net/ipv6/route.c (ffffffff820a2691)
Location: include/linux/jhash.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/ipv4/route.c (ffff800010c5ab78)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdeef4)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (c0d6a03c)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (c0de460c)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (c000000000d5c7c0)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (c000000000dfba7c)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffe0007c3f16)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082bc9e)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff8194a631)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bda8a)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In drivers/net/vxlan.c (ffffffff8176ca95)
Location: include/linux/jhash.h:164
Inline: True
```
```
In net/ipv4/route.c (ffffffff81904121)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197a87a)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff819b4e01)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2850a)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
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
In net/ipv4/route.c (ffffffff819be541)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33b3a)
Location: include/linux/jhash.h:164
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
```
</details>
</li>
</ul>

## Differences
