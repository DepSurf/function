# Function: <code>keepalive_probes</code>

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
In net/ipv4/tcp.c (ffffffff81767e88)
Location: include/net/tcp.h:1234
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81779b8d)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff817d439e)
Location: include/net/tcp.h:1248
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6d57)
Location: include/net/tcp.h:1248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff818040de)
Location: include/net/tcp.h:1305
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81817497)
Location: include/net/tcp.h:1305
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff818236fb)
Location: include/net/tcp.h:1345
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81837836)
Location: include/net/tcp.h:1345
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff818a32d4)
Location: include/net/tcp.h:1326
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6f7e)
Location: include/net/tcp.h:1326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff818f7f6f)
Location: include/net/tcp.h:1343
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c833)
Location: include/net/tcp.h:1343
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81924cc8)
Location: include/net/tcp.h:1401
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193aa50)
Location: include/net/tcp.h:1401
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81987ff0)
Location: include/net/tcp.h:1403
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ee00)
Location: include/net/tcp.h:1403
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819bf3f9)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d58a0)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81aaaa5c)
Location: include/net/tcp.h:1452
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2a76)
Location: include/net/tcp.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81ab7a78)
Location: include/net/tcp.h:1466
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace4a6)
Location: include/net/tcp.h:1466
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81aa2c45)
Location: include/net/tcp.h:1470
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9635)
Location: include/net/tcp.h:1470
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81b5edf0)
Location: include/net/tcp.h:1463
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76a71)
Location: include/net/tcp.h:1463
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81cedc6e)
Location: include/net/tcp.h:1508
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81d062a1)
Location: include/net/tcp.h:1508
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81eb44f5)
Location: include/net/tcp.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb612)
Location: include/net/tcp.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81f12385)
Location: include/net/tcp.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a15d)
Location: include/net/tcp.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81fd6748)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81feeca3)
Location: include/net/tcp.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffff800010c73744)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffff800010c88a2c)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (c0d81698)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (c0d97824)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (c000000000d79724)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (c000000000d95520)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffe0007d580a)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9764)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff8195f269)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81975710)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff81918d59)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f1d0)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819c9a39)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfee0)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
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
In net/ipv4/tcp.c (ffffffff819d3593)
Location: include/net/tcp.h:1425
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9ba0)
Location: include/net/tcp.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
</details>
</li>
</ul>

## Differences
