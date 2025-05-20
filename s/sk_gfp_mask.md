# Function: <code>sk_gfp_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e530b)
Location: include/net/sock.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f6c3)
Location: include/net/sock.h:783
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8181579b)
Location: include/net/sock.h:804
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891608)
Location: include/net/sock.h:804
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81835ba6)
Location: include/net/sock.h:818
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7c14)
Location: include/net/sock.h:818
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff818b51a6)
Location: include/net/sock.h:818
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193aa82)
Location: include/net/sock.h:818
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8190a715)
Location: include/net/sock.h:825
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199414c)
Location: include/net/sock.h:825
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819389b5)
Location: include/net/sock.h:853
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819caa6e)
Location: include/net/sock.h:853
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8199b8f5)
Location: include/net/sock.h:856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3969d)
Location: include/net/sock.h:856
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819d2315)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7022d)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81abf075)
Location: include/net/sock.h:907
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69e3d)
Location: include/net/sock.h:907
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81aca9d5)
Location: include/net/sock.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7891d)
Location: include/net/sock.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ab59c5)
Location: include/net/sock.h:922
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66c29)
Location: include/net/sock.h:922
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81b72a05)
Location: include/net/sock.h:934
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e7db)
Location: include/net/sock.h:934
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81d020b5)
Location: include/net/sock.h:974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb57e)
Location: include/net/sock.h:974
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ec7255)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd306)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c5c4)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_output.c (ffffffff81f25b15)
Location: include/net/sock.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2bfe6)
Location: include/net/sock.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd014)
Location: include/net/sock.h:1014
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_output.c (ffffffff81fea4d5)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0d1f)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc129)
Location: include/net/sock.h:985
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_output.c (ffff800010c84ea4)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38b78)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c0d9418c)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (c0e3af30)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c000000000d90e6c)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b520)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffe0007e6820)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875dae)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81972185)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f8bd)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8192bc55)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc67d)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819dc955)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a33d)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819e65d5)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86b7d)
Location: include/net/sock.h:861
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
</details>
</li>
</ul>

## Differences
