# Function: <code>tcp_ca_needs_ecn</code>

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
In net/ipv4/tcp_input.c (ffffffff8176a6ce)
Location: include/net/tcp.h:911
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81776371)
Location: include/net/tcp.h:911
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/tcp.h:911
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff817dc71b)
Location: include/net/tcp.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff817e4c32)
Location: include/net/tcp.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/tcp.h:928
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff8180c7f7)
Location: include/net/tcp.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81815082)
Location: include/net/tcp.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/tcp.h:975
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
In net/ipv4/tcp_input.c (ffffffff8182ca50)
Location: include/net/tcp.h:1027
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81835390)
Location: include/net/tcp.h:1027
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/tcp.h:1027
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
In net/ipv4/tcp_input.c (ffffffff818ab994)
Location: include/net/tcp.h:1029
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff818b4871)
Location: include/net/tcp.h:1029
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/tcp.h:1029
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
In net/ipv4/tcp_input.c (ffffffff81900d1a)
Location: include/net/tcp.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81909ec6)
Location: include/net/tcp.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81914173)
Location: include/net/tcp.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff8192ef26)
Location: include/net/tcp.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81938177)
Location: include/net/tcp.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81942923)
Location: include/net/tcp.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff8198d49a)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff8199b5d1)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6ef3)
Location: include/net/tcp.h:1088
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff819c3dfa)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff819d1ff9)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819ddbc3)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81ab3b9b)
Location: include/net/tcp.h:1129
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1a41)
Location: include/net/tcp.h:1129
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaec3)
Location: include/net/tcp.h:1129
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81abe50b)
Location: include/net/tcp.h:1134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81acd4ab)
Location: include/net/tcp.h:1134
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6e83)
Location: include/net/tcp.h:1134
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81aab0ca)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81ab56a6)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1f26)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81b67147)
Location: include/net/tcp.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81b726c0)
Location: include/net/tcp.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7fc7a)
Location: include/net/tcp.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81cf63a0)
Location: include/net/tcp.h:1138
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81d01d9e)
Location: include/net/tcp.h:1138
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0ff4a)
Location: include/net/tcp.h:1138
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81ebadb0)
Location: include/net/tcp.h:1151
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6f1e)
Location: include/net/tcp.h:1151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5bfa)
Location: include/net/tcp.h:1151
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81f19241)
Location: include/net/tcp.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81f257da)
Location: include/net/tcp.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34b26)
Location: include/net/tcp.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81fddaf0)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81fea0bf)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffaca6)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffff800010c76a50)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffff800010c84bb4)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffff800010c9109c)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (c0d84fa0)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (c0d93ea8)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c0d9fd24)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (c000000000d85630)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (c000000000d90a5c)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c000000000da06e8)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffe0007de4dc)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffe0007e655a)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0e96)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff81963c6a)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff81971e69)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8197da33)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff8191d75a)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff8192b939)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819374f3)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff819ce43a)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff819dc639)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819e8203)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
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
In net/ipv4/tcp_input.c (ffffffff819d7fca)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_output.c (ffffffff819e62b9)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1f33)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
```
</details>
</li>
</ul>

## Differences
