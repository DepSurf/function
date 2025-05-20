# Function: <code>sock_release_ownership</code>

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
In net/core/sock.c (ffffffff817022e4)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81777679)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81769545)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff817e469d)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81796455)
Location: include/net/sock.h:1411
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff818165fd)
Location: include/net/sock.h:1411
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff817b4615)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff818368ed)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff8182c878)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff818b5f6d)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff818769d8)
Location: include/net/sock.h:1433
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff8190b760)
Location: include/net/sock.h:1433
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81898868)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81939a30)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff818e2e08)
Location: include/net/sock.h:1481
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff8199dd03)
Location: include/net/sock.h:1481
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81914fe8)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff819d47c3)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff819e8108)
Location: include/net/sock.h:1540
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81ac10d5)
Location: include/net/sock.h:1540
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/mptcp/protocol.c (ffffffff81bac17c)
Location: include/net/sock.h:1540
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In net/core/sock.c (ffffffff819e7d78)
Location: include/net/sock.h:1555
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81accb45)
Location: include/net/sock.h:1555
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/mptcp/protocol.c (ffffffff81bbf809)
Location: include/net/sock.h:1555
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In net/core/sock.c (ffffffff819cdd48)
Location: include/net/sock.h:1571
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7d05)
Location: include/net/sock.h:1571
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81a7d528)
Location: include/net/sock.h:1581
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81b74ee5)
Location: include/net/sock.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81bf0ba8)
Location: include/net/sock.h:1806
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81d046b1)
Location: include/net/sock.h:1806
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81d9d278)
Location: include/net/sock.h:1827
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81ec962f)
Location: include/net/sock.h:1827
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81e0bac8)
Location: include/net/sock.h:1818
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81f2817f)
Location: include/net/sock.h:1818
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec84f0)
Location: include/net/sock.h:1793
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
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
In net/core/sock.c (ffff800010bade58)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffff800010c87308)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (c0ccb924)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (c0d96740)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (c000000000c83840)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (c000000000d93d38)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffe00073feb4)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffe0007e87b0)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff818b4fe8)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff81974633)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff8186ef38)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff8192e103)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81905fe8)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff819dee03)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
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
In net/core/sock.c (ffffffff81927018)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
```
In net/ipv4/tcp_output.c (ffffffff819e8aa3)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
</details>
</li>
</ul>

## Differences
