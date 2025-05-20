# Function: <code>dst_metric_advmss</code>

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
In net/ipv4/tcp_output.c (ffffffff81774b35)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cf2f)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fd5a)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0f39)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0a7e)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff817e4a3a)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eac38)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed283)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181de89)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185fd01)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81814e8a)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b588)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181db93)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f709)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891c61)
Location: include/net/dst.h:189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81835080)
Location: include/net/dst.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183be06)
Location: include/net/dst.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d9e2)
Location: include/net/dst.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff818731d9)
Location: include/net/dst.h:193
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8165)
Location: include/net/dst.h:193
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff818b4513)
Location: include/net/dst.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b9875)
Location: include/net/dst.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdaa6)
Location: include/net/dst.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3be9)
Location: include/net/dst.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193afeb)
Location: include/net/dst.h:195
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81909b29)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910121)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913926)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a513)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993a6b)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81937dd5)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e5a1)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819420d6)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c4d3)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca17f)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81999534)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a29f5)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a66d6)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e57e3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38d9f)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819cff23)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d95da)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcaf6)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c813)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f90f)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81abcf6a)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac64a6)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca61c)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dbd3)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b697f7)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ac86cc)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad37ca)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad658c)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bde3)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78261)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ab3408)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe865)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac15fc)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09ad3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b671aa)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81b7024b)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c395)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f058)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bccaa3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2eda3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81cff7ea)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c2c1)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e9c0)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d627c3)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc18c)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ec488a)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1d01)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed44a0)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d2f3)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d29e)
Location: include/net/dst.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81f231fa)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f309d6)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f334c0)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cdf3)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdd70)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81fe766c)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff68e6)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9627)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a783)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccbfc)
Location: include/net/dst.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffff800010c825e0)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cbc0)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f700)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8a24)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d382f0)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c0d91c58)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c0d9cce4)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c0d9f47c)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (c0de269c)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (c0e3b5f0)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c000000000d8e150)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ba94)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ebb4)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (c000000000df9274)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ba6c)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffe0007e4900)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebfb8)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efda0)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828fa6)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008754e6)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8196fd93)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197944a)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c966)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbea3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ef9f)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81929863)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932f0a)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936426)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978c93)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbd5f)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819da563)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3c1a)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7136)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26923)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79a1f)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819e41e5)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edd3a)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0e06)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31dd3)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86212)
Location: include/net/dst.h:167
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
</details>
</li>
</ul>

## Differences
