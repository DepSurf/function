# Function: <code>tcp_unlink_write_queue</code>

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
In net/ipv4/tcp.c (ffffffff81769c69)
Location: include/net/tcp.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176d1c9)
Location: include/net/tcp.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817773de)
Location: include/net/tcp.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In net/ipv4/tcp.c (ffffffff817d64b4)
Location: include/net/tcp.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff817daf42)
Location: include/net/tcp.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff817e65f9)
Location: include/net/tcp.h:1577
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff8180648e)
Location: include/net/tcp.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8180aab4)
Location: include/net/tcp.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81816d39)
Location: include/net/tcp.h:1652
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff81826b43)
Location: include/net/tcp.h:1703
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8182add9)
Location: include/net/tcp.h:1703
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81836fbc)
Location: include/net/tcp.h:1703
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff818a4a9b)
Location: include/net/tcp.h:1656
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff818b4229)
Location: include/net/tcp.h:1656
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff818fab30)
Location: include/net/tcp.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff8190976b)
Location: include/net/tcp.h:1672
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff819289e9)
Location: include/net/tcp.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81937a23)
Location: include/net/tcp.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp.c (ffffffff81987065)
Location: include/net/tcp.h:1773
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199bf65)
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff819bd7f5)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d29c5)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81aa920e)
Location: include/net/tcp.h:1833
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abf6df)
Location: include/net/tcp.h:1833
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81ab446e)
Location: include/net/tcp.h:1847
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81acb0fd)
Location: include/net/tcp.h:1847
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81a9f5ee)
Location: include/net/tcp.h:1851
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6159)
Location: include/net/tcp.h:1851
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81b5b3a0)
Location: include/net/tcp.h:1844
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b731b3)
Location: include/net/tcp.h:1844
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81cea11a)
Location: include/net/tcp.h:1900
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81d028b4)
Location: include/net/tcp.h:1900
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81eadd6a)
Location: include/net/tcp.h:1920
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7a94)
Location: include/net/tcp.h:1920
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81f0c1da)
Location: include/net/tcp.h:1933
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f26260)
Location: include/net/tcp.h:1933
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81fd029a)
Location: include/net/tcp.h:2035
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_remove_empty_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81feac1d)
Location: include/net/tcp.h:2035
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffff800010c6f38c)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c855dc)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (c0d7e56c)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d948d8)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (c000000000d760e4)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d917d0)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffe0007d4766)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6ee6)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff8195d665)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81972835)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff81917155)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192c305)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff819c7e35)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819dd005)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/ipv4/tcp.c (ffffffff819d1985)
Location: include/net/tcp.h:1795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e6c85)
Location: include/net/tcp.h:1795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
</details>
</li>
</ul>

## Differences
