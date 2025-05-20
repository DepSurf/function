# Function: <code>__ip_route_output_key_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rtable *__ip_route_output_key_hash(struct net *net, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81756290)
Location: net/ipv4/route.c:2128
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
```
**Symbols:**

```
ffffffff81756290-ffffffff81756b21: __ip_route_output_key_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rtable *__ip_route_output_key_hash(struct net *net, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c24b0)
Location: net/ipv4/route.c:2147
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
```
**Symbols:**

```
ffffffff817c24b0-ffffffff817c2dd0: __ip_route_output_key_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rtable *__ip_route_output_key_hash(struct net *net, struct flowi4 *fl4, int mp_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0b50)
Location: net/ipv4/route.c:2187
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_route_lookup
```
**Symbols:**

```
ffffffff817f0b50-ffffffff817f1487: __ip_route_output_key_hash (STB_GLOBAL)
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
