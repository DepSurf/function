# Function: <code>sk_mark_napi_id</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177d9d8)
Location: include/net/busy_poll.h:128
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff81786f50)
Location: include/net/busy_poll.h:128
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff817e1922)
Location: include/net/busy_poll.h:128
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f17e3)
Location: include/net/busy_poll.h:128
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff817ea658)
Location: include/net/busy_poll.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff817f4222)
Location: include/net/busy_poll.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff8184fc62)
Location: include/net/busy_poll.h:85
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f64e)
Location: include/net/busy_poll.h:85
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8181b188)
Location: include/net/busy_poll.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff81827d22)
Location: include/net/busy_poll.h:118
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81884142)
Location: include/net/busy_poll.h:118
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891593)
Location: include/net/busy_poll.h:118
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8183b83e)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d861)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff818489a0)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff818aa4d1)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7ab9)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff818bb274)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcf71)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff818c83c8)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff8192cfe1)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a929)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819109df)
Location: include/net/busy_poll.h:149
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912dd6)
Location: include/net/busy_poll.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8191e2b0)
Location: include/net/busy_poll.h:149
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81984c71)
Location: include/net/busy_poll.h:149
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993ff6)
Location: include/net/busy_poll.h:149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819334af)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f287)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941581)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8194cefc)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bb251)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca8fe)
Location: include/net/busy_poll.h:134
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81996f0f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a378f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5b75)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819b16b4)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a29e62)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39525)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819cda8f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da3af)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc935)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819e8418)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a60982)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a700b5)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ab9c5f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac764f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a05)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ad635d)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b5748a)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69cc5)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ac508f)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad2f8f)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5955)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ae26ab)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b659aa)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b787a5)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ab02af)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abdbbf)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09b5)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81acd865)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b56147)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66aa5)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81b6d0c1)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b094)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e375)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81b8c242)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81c1c7c4)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e655)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81cfc541)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ba35)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1c83c)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81db904c)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb2ec)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ec10e1)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1995)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee3845)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81f88fbd)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c37c)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81f1f641)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f30109)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff81f430b8)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81fe837e)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffcdce)
Location: include/net/busy_poll.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81fe3d09)
Location: include/net/busy_poll.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff5f99)
Location: include/net/busy_poll.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/udp.c (ffffffff82009021)
Location: include/net/busy_poll.h:131
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff820b6ed2)
Location: include/net/busy_poll.h:131
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cbeee)
Location: include/net/busy_poll.h:131
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffff800010c80604)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d450)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8a8)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffff800010c9d85c)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffff800010d26574)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d389e4)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (c0d8f7dc)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (c0d9c5ac)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c0d9e974)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c0dab2a8)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c0e29b74)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c0e3ad98)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (c000000000d8b234)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9c55c)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8b4)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c000000000daf130)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c000000000e561d0)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b334)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffe0007e259c)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed8ba)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efbca)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffe0007fa856)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffe000866c06)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875c3a)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff8196d8ff)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a21f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7a5)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81988288)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a00012)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f745)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819273ef)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933cdf)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936265)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81941d48)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bcdd2)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc505)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819d80cf)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e49ef)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6f75)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819f2a58)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a6aa92)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a1c5)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819e1d0f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eeb2f)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c45)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819fcf58)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a770a2)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86a05)
Location: include/net/busy_poll.h:122
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
</details>
</li>
</ul>

## Differences
