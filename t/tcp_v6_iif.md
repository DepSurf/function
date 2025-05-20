# Function: <code>tcp_v6_iif</code>

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
In net/ipv6/tcp_ipv6.c (ffffffff817ef9b9)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/syncookies.c (ffffffff817ff792)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff8186070f)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff8186f0ff)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff818926c0)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff818a206a)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff818b8cfa)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff818c8706)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff8193bbbe)
Location: include/net/tcp.h:829
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff8194bccb)
Location: include/net/tcp.h:829
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81994189)
Location: include/net/tcp.h:842
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff819a4fdd)
Location: include/net/tcp.h:842
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff819caaab)
Location: include/net/tcp.h:880
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff819dba99)
Location: include/net/tcp.h:880
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81a396e0)
Location: include/net/tcp.h:881
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff81a4a74e)
Location: include/net/tcp.h:881
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81a70270)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff81a81322)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81b69e80)
Location: include/net/tcp.h:913
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff81b7bfd0)
Location: include/net/tcp.h:913
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81b78960)
Location: include/net/tcp.h:921
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (ffffffff81b8b001)
Location: include/net/tcp.h:921
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81b66c6c)
Location: include/net/tcp.h:901
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81b79e64)
Location: include/net/tcp.h:901
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81c2e829)
Location: include/net/tcp.h:894
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81c44b30)
Location: include/net/tcp.h:894
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81dcb488)
Location: include/net/tcp.h:909
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81de3b31)
Location: include/net/tcp.h:909
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81f9c518)
Location: include/net/tcp.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81fb61b1)
Location: include/net/tcp.h:922
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81ffcf68)
Location: include/net/tcp.h:917
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff820168c9)
Location: include/net/tcp.h:917
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff820cc088)
Location: include/net/tcp.h:954
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
```
```
In net/ipv6/syncookies.c (ffffffff820e58dc)
Location: include/net/tcp.h:954
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffff800010d38bcc)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffff800010d4c9fc)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (c0e3af74)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
```
```
In net/ipv6/syncookies.c (c0e4dd60)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (c000000000e6b5a4)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (c000000000e83274)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffe000875df0)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffe000885772)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81a0f900)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff81a209b2)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff819cc6c0)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff819dd772)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81a7a380)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff81a8b432)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/tcp_ipv6.c (ffffffff81a86bc0)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/syncookies.c (ffffffff81a98038)
Location: include/net/tcp.h:902
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>

## Differences
