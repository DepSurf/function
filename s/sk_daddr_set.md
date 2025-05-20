# Function: <code>sk_daddr_set</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177b1c0)
Location: include/net/inet_hashtables.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/syncookies.c (ffffffff817ab5c0)
Location: include/net/inet_hashtables.h:350
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff817eab2a)
Location: include/net/inet_hashtables.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff818190b3)
Location: include/net/inet_hashtables.h:362
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff8181b47a)
Location: include/net/inet_hashtables.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8184a927)
Location: include/net/inet_hashtables.h:362
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff8183bcfe)
Location: include/net/inet_hashtables.h:366
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8186e2f9)
Location: include/net/inet_hashtables.h:366
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff818b976f)
Location: include/net/inet_hashtables.h:369
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff818eec89)
Location: include/net/inet_hashtables.h:369
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff8191001f)
Location: include/net/inet_hashtables.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8194559b)
Location: include/net/inet_hashtables.h:386
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff8193e49f)
Location: include/net/inet_hashtables.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8197594b)
Location: include/net/inet_hashtables.h:397
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff819a28d2)
Location: include/net/inet_hashtables.h:393
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff819df49c)
Location: include/net/inet_hashtables.h:393
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff819d94c2)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a16503)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac638e)
Location: include/net/inet_hashtables.h:404
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b07513)
Location: include/net/inet_hashtables.h:404
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad3691)
Location: include/net/inet_hashtables.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b15913)
Location: include/net/inet_hashtables.h:405
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81abe721)
Location: include/net/inet_hashtables.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81b03725)
Location: include/net/inet_hashtables.h:405
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7c251)
Location: include/net/inet_hashtables.h:411
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81bc59b5)
Location: include/net/inet_hashtables.h:411
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0c181)
Location: include/net/inet_hashtables.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81d5ac41)
Location: include/net/inet_hashtables.h:355
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed1bc1)
Location: include/net/inet_hashtables.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f250b1)
Location: include/net/inet_hashtables.h:455
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81f30891)
Location: include/net/inet_hashtables.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81f84c41)
Location: include/net/inet_hashtables.h:455
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff67a1)
Location: include/net/inet_hashtables.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff8204b44f)
Location: include/net/inet_hashtables.h:512
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffff800010c8cafc)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffff800010cd2208)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (c0d9cbf8)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (c0ddc0ac)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (c000000000d9b9a0)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (c000000000df0674)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffe0007ebefc)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffe0008235cc)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81979332)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff819b5b93)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff81932df2)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81972983)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff819e3b02)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a20433)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/tcp_ipv4.c (ffffffff819edc22)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/syncookies.c (ffffffff81a2b933)
Location: include/net/inet_hashtables.h:399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
</details>
</li>
</ul>

## Differences
