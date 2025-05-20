# Function: <code>inet_sk_bound_dev_eq</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f68b)
Location: include/net/inet_hashtables.h:192
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3278)
Location: include/net/inet_hashtables.h:192
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81981fef)
Location: include/net/inet_hashtables.h:188
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51fbc)
Location: include/net/inet_hashtables.h:188
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819b884f)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88bbc)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81aa3457)
Location: include/net/inet_hashtables.h:200
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84534)
Location: include/net/inet_hashtables.h:200
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81aad986)
Location: include/net/inet_hashtables.h:200
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93d82)
Location: include/net/inet_hashtables.h:200
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81a98a46)
Location: include/net/inet_hashtables.h:200
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82e92)
Location: include/net/inet_hashtables.h:200
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81b53f25)
Location: include/net/inet_hashtables.h:206
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ef60)
Location: include/net/inet_hashtables.h:206
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81ce2921)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81d1f044)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff81dbbc98)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def789)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3db3)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81ee615c)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff81f8bdc0)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3859)
Location: include/net/inet_sock.h:152
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f025fe)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81f4595c)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff81fec560)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820246a4)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc69be)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff8200baac)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff820ba170)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f39b4)
Location: include/net/inet_sock.h:153
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffff800010c69cbc)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d5589c)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (c0d78f70)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (c0e55e9c)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (c000000000d6ece4)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e7f8)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffe0007cfacc)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d08a)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819586bf)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a2824c)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819121af)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e500c)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819c2e8f)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93dfc)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819cc95f)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9ff4c)
Location: include/net/inet_hashtables.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
</ul>

## Differences
