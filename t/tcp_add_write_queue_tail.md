# Function: <code>tcp_add_write_queue_tail</code>

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
In net/ipv4/tcp.c (ffffffff81765d65)
Location: include/net/tcp.h:1525
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff817790dc)
Location: include/net/tcp.h:1525
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff817d21e5)
Location: include/net/tcp.h:1540
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff817e626c)
Location: include/net/tcp.h:1540
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81801fa6)
Location: include/net/tcp.h:1614
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8181698c)
Location: include/net/tcp.h:1614
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818220db)
Location: include/net/tcp.h:1665
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81836c96)
Location: include/net/tcp.h:1665
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818a114b)
Location: include/net/tcp.h:1639
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff818b6347)
Location: include/net/tcp.h:1639
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818f5ce3)
Location: include/net/tcp.h:1655
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8190bb87)
Location: include/net/tcp.h:1655
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81923940)
Location: include/net/tcp.h:1727
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81939e54)
Location: include/net/tcp.h:1727
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff8198635f)
Location: include/net/tcp.h:1756
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8199e106)
Location: include/net/tcp.h:1756
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff819bcaef)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819d4bc8)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81aa7a3f)
Location: include/net/tcp.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1588)
Location: include/net/tcp.h:1816
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81ab20bf)
Location: include/net/tcp.h:1830
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81accff8)
Location: include/net/tcp.h:1830
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81a9d34f)
Location: include/net/tcp.h:1834
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ab81c8)
Location: include/net/tcp.h:1834
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81b5921f)
Location: include/net/tcp.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81b753a8)
Location: include/net/tcp.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81ce97c9)
Location: include/net/tcp.h:1883
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81d04c1e)
Location: include/net/tcp.h:1883
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81ead509)
Location: include/net/tcp.h:1903
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9c6e)
Location: include/net/tcp.h:1903
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81f0bc19)
Location: include/net/tcp.h:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81f287be)
Location: include/net/tcp.h:1916
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81fcfcc9)
Location: include/net/tcp.h:2018
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81fed24e)
Location: include/net/tcp.h:2018
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffff800010c6ed3c)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffff800010c87820)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (c0d7d85c)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (c0d96b6c)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (c000000000d74e94)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (c000000000d943a0)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffe0007d3af2)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8b94)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff8195c95f)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81974a38)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff8191644f)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8192e4f8)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff819c712f)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819df208)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff819d0c7f)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff819e8ea8)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
```
</details>
</li>
</ul>

## Differences
