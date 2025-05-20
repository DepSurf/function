# Function: <code>INET_ECN_xmit</code>

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
In net/ipv4/tcp_output.c (ffffffff817760be)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_cong.c (ffffffff81780710)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff817e5030)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff817edcbf)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff818154ba)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e63f)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff818353cc)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8183ec6d)
Location: include/net/inet_ecn.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff818b48ac)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff818be4bd)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff8190a463)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81914180)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff8193870b)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81942930)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff8199b7b4)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6f00)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff819d21ea)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819ddbd0)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ac1ae8)
Location: include/net/inet_ecn.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaed0)
Location: include/net/inet_ecn.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81acd545)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad7430)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ab5870)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac251a)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81b7289b)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81b8028e)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81d01de2)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81d1066e)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ec70af)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed638e)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81f25965)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81f352ae)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81fea24a)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb42e)
Location: include/net/inet_ecn.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffff800010c84bf4)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffff800010c910a8)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (c0d93ef0)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c0d9fd3c)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (c000000000d90c70)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c000000000da0704)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffe0007e658a)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0ea0)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff8197205a)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8197da40)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff8192bb2a)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81937500)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff819dc82a)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819e8210)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff819e64aa)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1f40)
Location: include/net/inet_ecn.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
</details>
</li>
</ul>

## Differences
