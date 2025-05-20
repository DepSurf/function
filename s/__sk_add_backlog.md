# Function: <code>__sk_add_backlog</code>

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
In net/core/sock.c (ffffffff81703baa)
Location: include/net/sock.h:817
Inline: True
Inline callers:
  - net/core/sock.c:sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ec40)
Location: include/net/sock.h:817
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f2f8)
Location: include/net/sock.h:817
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81789981)
Location: include/net/sock.h:817
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff817e42d7)
Location: include/net/sock.h:817
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f232a)
Location: include/net/sock.h:817
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
In net/core/sock.c (ffffffff8176a649)
Location: include/net/sock.h:819
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec12a)
Location: include/net/sock.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec7fc)
Location: include/net/sock.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f708c)
Location: include/net/sock.h:819
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81852614)
Location: include/net/sock.h:819
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860ca9)
Location: include/net/sock.h:819
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
In net/core/sock.c (ffffffff81797738)
Location: include/net/sock.h:840
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b2ea)
Location: include/net/sock.h:840
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d0ec)
Location: include/net/sock.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff817b5332)
Location: include/net/sock.h:854
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183ba96)
Location: include/net/sock.h:854
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d908)
Location: include/net/sock.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff8182d7a9)
Location: include/net/sock.h:854
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb4c1)
Location: include/net/sock.h:854
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd01a)
Location: include/net/sock.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81877b6e)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910f7a)
Location: include/net/sock.h:861
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e73)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff8189805b)
Location: include/net/sock.h:889
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f5e4)
Location: include/net/sock.h:889
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941630)
Location: include/net/sock.h:889
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff818e25cd)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39c5)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c31)
Location: include/net/sock.h:892
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff8191479f)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6c7)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc9f1)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff819e66c8)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7876)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ad0)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff819e5fb8)
Location: include/net/sock.h:963
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad324e)
Location: include/net/sock.h:963
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a20)
Location: include/net/sock.h:963
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff819ccbf8)
Location: include/net/sock.h:967
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe2ee)
Location: include/net/sock.h:967
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a7f)
Location: include/net/sock.h:967
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81a7c338)
Location: include/net/sock.h:979
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bde7)
Location: include/net/sock.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e443)
Location: include/net/sock.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81bf00b3)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0bcfa)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e3c6)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81d9c2cf)
Location: include/net/sock.h:1057
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0c1c)
Location: include/net/sock.h:1057
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3e76)
Location: include/net/sock.h:1057
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81e0ab17)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f303dc)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32e6e)
Location: include/net/sock.h:1059
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff81ec7507)
Location: include/net/sock.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff626b)
Location: include/net/sock.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8fbe)
Location: include/net/sock.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffff800010bad5b4)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8da7c)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f95c)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (c0ccb1b0)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9c7a8)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c0d9ea18)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (c000000000c82e30)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b30c)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e980)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffe00073f7d0)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee02c)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc9e)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff818b479f)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a537)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c861)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff8186e6ef)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933ff7)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936321)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff8190579f)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d07)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7031)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
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
In net/core/sock.c (ffffffff819267ad)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee067)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0cff)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
</details>
</li>
</ul>

## Differences
