# Function: <code>tcp_checksum_complete</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177d900)
Location: include/net/tcp.h:1142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f16f9)
Location: include/net/tcp.h:1142
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_input.c (ffffffff817dfd83)
Location: include/net/tcp.h:1150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eba4b)
Location: include/net/tcp.h:1150
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860574)
Location: include/net/tcp.h:1150
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81810153)
Location: include/net/tcp.h:1205
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c3c1)
Location: include/net/tcp.h:1205
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189250b)
Location: include/net/tcp.h:1205
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff8182fe56)
Location: include/net/tcp.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cb7b)
Location: include/net/tcp.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8b5a)
Location: include/net/tcp.h:1240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff818af921)
Location: include/net/tcp.h:1231
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc283)
Location: include/net/tcp.h:1231
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ba1f)
Location: include/net/tcp.h:1231
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff8190504c)
Location: include/net/tcp.h:1248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911faf)
Location: include/net/tcp.h:1248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994ee0)
Location: include/net/tcp.h:1248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819331e1)
Location: include/net/tcp.h:1318
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940778)
Location: include/net/tcp.h:1318
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb7c3)
Location: include/net/tcp.h:1318
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81996ac2)
Location: include/net/tcp.h:1320
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4cb2)
Location: include/net/tcp.h:1320
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a3f8)
Location: include/net/tcp.h:1320
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819cd642)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db9b2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70f99)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ab97d5)
Location: include/net/tcp.h:1356
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8aa0)
Location: include/net/tcp.h:1356
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a60d)
Location: include/net/tcp.h:1356
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ac4bcb)
Location: include/net/tcp.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4a40)
Location: include/net/tcp.h:1363
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b792ab)
Location: include/net/tcp.h:1363
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81aafcb7)
Location: include/net/tcp.h:1355
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfaf8)
Location: include/net/tcp.h:1355
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67de1)
Location: include/net/tcp.h:1355
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81b6ca92)
Location: include/net/tcp.h:1348
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d663)
Location: include/net/tcp.h:1348
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fa70)
Location: include/net/tcp.h:1348
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81cfbf4a)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d5ff)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccc71)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81ec0aca)
Location: include/net/tcp.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed31db)
Location: include/net/tcp.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dd86)
Location: include/net/tcp.h:1393
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81f1f03a)
Location: include/net/tcp.h:1391
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ee0)
Location: include/net/tcp.h:1391
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe8b7)
Location: include/net/tcp.h:1391
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81fe36d7)
Location: include/net/tcp.h:1428
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7ed4)
Location: include/net/tcp.h:1428
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd76a)
Location: include/net/tcp.h:1428
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffff800010c801a0)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8edd0)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d392a0)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (c0d8f33c)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (c0d9dc88)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bdf0)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (c000000000d8ad0c)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d97c)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c880)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffe0007e219a)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeff8)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087662e)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff8196d4b2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b822)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10629)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff81926fa2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819352e2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd3e9)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819d7c82)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ff2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b0a9)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/ipv4/tcp_input.c (ffffffff819e18bb)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efcb2)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a878e9)
Location: include/net/tcp.h:1341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
</details>
</li>
</ul>

## Differences
