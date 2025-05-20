# Function: <code>tcp_bpf_ca_needs_ecn</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182ca69)
Location: include/net/tcp.h:2092
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8183534d)
Location: include/net/tcp.h:2092
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff818ab9a5)
Location: include/net/tcp.h:2057
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b4828)
Location: include/net/tcp.h:2057
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81900d27)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81909e71)
Location: include/net/tcp.h:2116
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff8192ef37)
Location: include/net/tcp.h:2196
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81938122)
Location: include/net/tcp.h:2196
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819924d4)
Location: include/net/tcp.h:2228
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8199b584)
Location: include/net/tcp.h:2228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819c8b8d)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819d1fac)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81ab3bc6)
Location: include/net/tcp.h:2309
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1a52)
Location: include/net/tcp.h:2309
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
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
In net/ipv4/tcp_input.c (ffffffff81abe532)
Location: include/net/tcp.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
```
```
In net/ipv4/tcp_output.c (ffffffff81acd4bc)
Location: include/net/tcp.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad40e6)
Location: include/net/tcp.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b773f5)
Location: include/net/tcp.h:2333
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81aab0de)
Location: include/net/tcp.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5664)
Location: include/net/tcp.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf183)
Location: include/net/tcp.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65efd)
Location: include/net/tcp.h:2338
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81b6715b)
Location: include/net/tcp.h:2330
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81b7266e)
Location: include/net/tcp.h:2330
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7ccbb)
Location: include/net/tcp.h:2330
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2df7d)
Location: include/net/tcp.h:2330
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81cf63bc)
Location: include/net/tcp.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81d01d4c)
Location: include/net/tcp.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cbf3)
Location: include/net/tcp.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb8bd)
Location: include/net/tcp.h:2390
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81ebadcc)
Location: include/net/tcp.h:2438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6ecc)
Location: include/net/tcp.h:2438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2633)
Location: include/net/tcp.h:2438
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c9bd)
Location: include/net/tcp.h:2438
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81f1925d)
Location: include/net/tcp.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81f25788)
Location: include/net/tcp.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31313)
Location: include/net/tcp.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd40d)
Location: include/net/tcp.h:2463
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffffffff81fddb0c)
Location: include/net/tcp.h:2659
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81fea06d)
Location: include/net/tcp.h:2659
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff72a3)
Location: include/net/tcp.h:2659
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cb181)
Location: include/net/tcp.h:2659
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/ipv4/tcp_input.c (ffff800010c7a7a0)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffff800010c84b84)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (c0d88714)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c0d93e5c)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (c000000000d857e0)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d90a28)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffe0007de4e6)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6506)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819689fd)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81971e1c)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819224ed)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8192b8ec)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819d31cd)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819dc5ec)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp_input.c (ffffffff819dcd73)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819e626c)
Location: include/net/tcp.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
```
</details>
</li>
</ul>

## Differences
