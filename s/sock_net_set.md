# Function: <code>sock_net_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817013d2)
Location: include/net/sock.h:2217
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767623)
Location: include/net/sock.h:2199
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8179461f)
Location: include/net/sock.h:2266
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4872)
Location: include/net/sock.h:2293
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cad2)
Location: include/net/sock.h:2307
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818775ee)
Location: include/net/sock.h:2314
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81897a3e)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff8190be95)
Location: include/net/sock.h:2445
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff818e1f5b)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff8196d65e)
Location: include/net/sock.h:2458
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff8191412b)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff819a40c9)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff819e6945)
Location: include/net/sock.h:2531
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff81a7ec0d)
Location: include/net/sock.h:2531
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff819e616b)
Location: include/net/sock.h:2552
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff81a88540)
Location: include/net/sock.h:2552
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff819cc222)
Location: include/net/sock.h:2588
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff81a717a0)
Location: include/net/sock.h:2588
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b892)
Location: include/net/sock.h:2647
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81bef03a)
Location: include/net/sock.h:622
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a60e)
Location: include/net/sock.h:622
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff81d24593)
Location: include/net/sock.h:622
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv6/icmp.c (ffffffff81dc01bf)
Location: include/net/sock.h:622
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
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
In net/core/sock.c (ffffffff81d9b87a)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81e6b7c9)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfe9e)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff81eebd73)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv6/icmp.c (ffffffff81f9092f)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
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
In net/core/sock.c (ffffffff81e09f1a)
Location: include/net/sock.h:655
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec7815)
Location: include/net/sock.h:655
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2eb4a)
Location: include/net/sock.h:655
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff81f4bb4a)
Location: include/net/sock.h:655
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv6/icmp.c (ffffffff81ff11af)
Location: include/net/sock.h:655
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
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
In net/core/sock.c (ffffffff81ec690a)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f8ab77)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3964)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff82011c5a)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv6/icmp.c (ffffffff820bed8d)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
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
In net/core/sock.c (ffff800010bab128)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffff800010c53520)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (c0cc9bbc)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (c0d62e40)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (c000000000c81918)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (c000000000d52bd0)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffe00073eb14)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffe0007bde02)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff818b412b)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff81943f39)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff8186e07b)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff818fda29)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff8190512b)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff819950c9)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/sock.c (ffffffff819261fb)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/bpf/test_run.c (ffffffff819b7c49)
Location: include/net/sock.h:2479
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
</ul>

## Differences
