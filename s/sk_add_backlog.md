# Function: <code>sk_add_backlog</code>

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
In net/core/sock.c (ffffffff81703b7e)
Location: include/net/sock.h:844
Inline: True
Inline callers:
  - net/core/sock.c:sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ec0f)
Location: include/net/sock.h:844
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81789955)
Location: include/net/sock.h:844
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff817e42ab)
Location: include/net/sock.h:844
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f22f9)
Location: include/net/sock.h:844
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff8176a61d)
Location: include/net/sock.h:846
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec0f9)
Location: include/net/sock.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff817f705d)
Location: include/net/sock.h:846
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff818525e5)
Location: include/net/sock.h:846
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860c78)
Location: include/net/sock.h:846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff8179770c)
Location: include/net/sock.h:867
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b2c5)
Location: include/net/sock.h:867
Inline: True
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
In net/core/sock.c (ffffffff817b5306)
Location: include/net/sock.h:881
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183ba6a)
Location: include/net/sock.h:881
Inline: True
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
In net/core/sock.c (ffffffff8182d782)
Location: include/net/sock.h:881
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb49a)
Location: include/net/sock.h:881
Inline: True
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
In net/core/sock.c (ffffffff81877af2)
Location: include/net/sock.h:888
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910f51)
Location: include/net/sock.h:888
Inline: True
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
In net/core/sock.c (ffffffff81897fe2)
Location: include/net/sock.h:916
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f5b0)
Location: include/net/sock.h:916
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff818e254b)
Location: include/net/sock.h:919
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a399d)
Location: include/net/sock.h:919
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81914723)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da69f)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff819e6643)
Location: include/net/sock.h:975
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac784e)
Location: include/net/sock.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff819e5f33)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3226)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff819ccb73)
Location: include/net/sock.h:994
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe2c6)
Location: include/net/sock.h:994
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81a7c2b3)
Location: include/net/sock.h:1006
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bdbf)
Location: include/net/sock.h:1006
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81bf0024)
Location: include/net/sock.h:1046
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bcd1)
Location: include/net/sock.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81d9c26d)
Location: include/net/sock.h:1084
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0bf1)
Location: include/net/sock.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81e0aab1)
Location: include/net/sock.h:1086
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f303b1)
Location: include/net/sock.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81ec74a1)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6240)
Location: include/net/sock.h:1063
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffff800010bad598)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8da5c)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (c0ccb134)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9c784)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (c000000000c82d24)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b2e8)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffe00073f75e)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee00c)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff818b4723)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a50f)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff8186e673)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933fcf)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81905723)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4cdf)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
In net/core/sock.c (ffffffff81926733)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee03f)
Location: include/net/sock.h:929
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
</details>
</li>
</ul>

## Differences
