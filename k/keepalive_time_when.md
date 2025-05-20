# Function: <code>keepalive_time_when</code>

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
In net/ipv4/tcp.c (ffffffff81767e09)
Location: include/net/tcp.h:1229
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817734d6)
Location: include/net/tcp.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81779a22)
Location: include/net/tcp.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f027)
Location: include/net/tcp.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff817d4377)
Location: include/net/tcp.h:1241
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817e0366)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6bf2)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec4d9)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff818040b7)
Location: include/net/tcp.h:1298
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81810743)
Location: include/net/tcp.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81817332)
Location: include/net/tcp.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181cdc3)
Location: include/net/tcp.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff8182373f)
Location: include/net/tcp.h:1338
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818306c1)
Location: include/net/tcp.h:1338
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff818376d8)
Location: include/net/tcp.h:1338
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d5ca)
Location: include/net/tcp.h:1338
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff818a32aa)
Location: include/net/tcp.h:1319
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818afbb1)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6e02)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bccbd)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff818f7f48)
Location: include/net/tcp.h:1336
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819052f1)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c687)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912b1d)
Location: include/net/tcp.h:1336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81924ce2)
Location: include/net/tcp.h:1394
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819334ea)
Location: include/net/tcp.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8193a9b1)
Location: include/net/tcp.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819412e7)
Location: include/net/tcp.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff8198801e)
Location: include/net/tcp.h:1396
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81996f4a)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ed61)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a58ac)
Location: include/net/tcp.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff819bf427)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cdaca)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5801)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc66c)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81aaaa8b)
Location: include/net/tcp.h:1445
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9c9a)
Location: include/net/tcp.h:1445
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac29d3)
Location: include/net/tcp.h:1445
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac973c)
Location: include/net/tcp.h:1445
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81ab7aa7)
Location: include/net/tcp.h:1459
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ac50cd)
Location: include/net/tcp.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace403)
Location: include/net/tcp.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad567c)
Location: include/net/tcp.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81aa2c75)
Location: include/net/tcp.h:1463
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab02ed)
Location: include/net/tcp.h:1463
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9593)
Location: include/net/tcp.h:1463
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac06ec)
Location: include/net/tcp.h:1463
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81b5ee1d)
Location: include/net/tcp.h:1456
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d0ff)
Location: include/net/tcp.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81b769cf)
Location: include/net/tcp.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e09e)
Location: include/net/tcp.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81ced801)
Location: include/net/tcp.h:1500
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc587)
Location: include/net/tcp.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81d061ef)
Location: include/net/tcp.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0dfdc)
Location: include/net/tcp.h:1500
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81eb3fd3)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1127)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb55d)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3acc)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81f12999)
Location: include/net/tcp.h:1521
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f687)
Location: include/net/tcp.h:1521
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a0a9)
Location: include/net/tcp.h:1521
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32aac)
Location: include/net/tcp.h:1521
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81fd6e8a)
Location: include/net/tcp.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81fe3d4f)
Location: include/net/tcp.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81feec19)
Location: include/net/tcp.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8afc)
Location: include/net/tcp.h:1591
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffff800010c73730)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c80634)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffff800010c889a8)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8fb40)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (c0d81608)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d8f814)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (c0d9778c)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (c0d9e728)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (c000000000d79524)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d8b268)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (c000000000d9547c)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e5fc)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffe0007d57dc)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007e25c6)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e96f0)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef9b4)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff8195f297)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8196d93a)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81975671)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c4dc)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff81918d87)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192742a)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f131)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935f9c)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff819c9a67)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d810a)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfe41)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6cac)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
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
In net/ipv4/tcp.c (ffffffff819d35c1)
Location: include/net/tcp.h:1418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819e1d4a)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9b01)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f097c)
Location: include/net/tcp.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
</details>
</li>
</ul>

## Differences
