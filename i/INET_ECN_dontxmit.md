# Function: <code>INET_ECN_dontxmit</code>

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
In net/ipv4/tcp_output.c (ffffffff81776383)
Location: include/net/inet_ecn.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff817806cb)
Location: include/net/inet_ecn.h:58
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
In net/ipv4/tcp_output.c (ffffffff817e32f3)
Location: include/net/inet_ecn.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff817edc7c)
Location: include/net/inet_ecn.h:58
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
In net/ipv4/tcp_output.c (ffffffff818139c2)
Location: include/net/inet_ecn.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e5fc)
Location: include/net/inet_ecn.h:58
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
In net/ipv4/tcp_output.c (ffffffff81833b9d)
Location: include/net/inet_ecn.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8183ec92)
Location: include/net/inet_ecn.h:58
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
In net/ipv4/tcp_output.c (ffffffff818b2f21)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff818be4e2)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff819085db)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819141c5)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff81936820)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81942975)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff8199ac2c)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6f45)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff819d1695)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819ddc15)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff81abe799)
Location: include/net/inet_ecn.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaf18)
Location: include/net/inet_ecn.h:60
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
In net/ipv4/tcp_output.c (ffffffff81aca0b3)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad7505)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81ab4f4b)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac25f1)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81b71f1b)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81b8038b)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81d01621)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81d1070f)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81ec6781)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed642f)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81f24ef9)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81f35347)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffffffff81fe97ce)
Location: include/net/inet_ecn.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb4c7)
Location: include/net/inet_ecn.h:61
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
In net/ipv4/tcp_output.c (ffff800010c84248)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffff800010c910f8)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (c0d93504)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c0d9fd7c)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (c000000000d8fe70)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (c000000000da0760)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffe0007e5d48)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0ef0)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff81971505)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff8197da85)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff8192afd5)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff81937545)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff819dbcd5)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819e8255)
Location: include/net/inet_ecn.h:59
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
In net/ipv4/tcp_output.c (ffffffff819e5955)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1f85)
Location: include/net/inet_ecn.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
</details>
</li>
</ul>

## Differences
