# Function: <code>__skb_header_release</code>

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
In net/core/skbuff.c (ffffffff8170c7b6)
Location: include/linux/skbuff.h:1278
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81765d6c)
Location: include/linux/skbuff.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81774465)
Location: include/linux/skbuff.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/core/skbuff.c (ffffffff8176f7f9)
Location: include/linux/skbuff.h:1379
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff817d21ec)
Location: include/linux/skbuff.h:1379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff817e1315)
Location: include/linux/skbuff.h:1379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8179960f)
Location: include/linux/skbuff.h:1394
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81801fc6)
Location: include/linux/skbuff.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff818117e5)
Location: include/linux/skbuff.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff817b89e6)
Location: include/linux/skbuff.h:1387
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff818220fb)
Location: include/linux/skbuff.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81831a55)
Location: include/linux/skbuff.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff818313a6)
Location: include/linux/skbuff.h:1469
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff818a116b)
Location: include/linux/skbuff.h:1469
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff818b47d4)
Location: include/linux/skbuff.h:1469
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8187b874)
Location: include/linux/skbuff.h:1480
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff818f5cc8)
Location: include/linux/skbuff.h:1480
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81909e13)
Location: include/linux/skbuff.h:1480
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8189c68c)
Location: include/linux/skbuff.h:1549
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81923928)
Location: include/linux/skbuff.h:1549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819380c7)
Location: include/linux/skbuff.h:1549
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff818e6f15)
Location: include/linux/skbuff.h:1639
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81986358)
Location: include/linux/skbuff.h:1639
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8199b51e)
Location: include/linux/skbuff.h:1639
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff819192f5)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff819bcae8)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f3e)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff819f2908)
Location: include/linux/skbuff.h:1660
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81aa7a38)
Location: include/linux/skbuff.h:1660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81abadfb)
Location: include/linux/skbuff.h:1660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff819f28f8)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81ab20b8)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ac619b)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff819d8b28)
Location: include/linux/skbuff.h:1697
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81a9d337)
Location: include/linux/skbuff.h:1697
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ab13ab)
Location: include/linux/skbuff.h:1697
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff81a88ac0)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81b59207)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e2bb)
Location: include/linux/skbuff.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/gro.c (ffffffff81c549e9)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81ce97b5)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81cfd73b)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/gro.c (ffffffff81e0a196)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81ead4f5)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ec234b)
Location: include/linux/skbuff.h:1935
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/gro.c (ffffffff81e7c99a)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81f0bc05)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81f2095b)
Location: include/linux/skbuff.h:1971
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/gro.c (ffffffff81f3ccea)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81fcfcb5)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81fe505b)
Location: include/linux/skbuff.h:1978
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffff800010bb24a4)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffff800010c84b0c)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (c0ccfc94)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (c0d7d84c)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (c0d93df4)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (c000000000c88260)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (c000000000d74e90)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (c000000000d909b0)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffe000743d10)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffe0007d3ac0)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffe0007e64b2)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff818b92f5)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff8195c958)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81971dae)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff81873245)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff81916448)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8192b87e)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8190a2f5)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff819c7128)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819dc57e)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8192b3f5)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/ipv4/tcp.c (ffffffff819d0c78)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819e61fe)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
</details>
</li>
</ul>

## Differences
