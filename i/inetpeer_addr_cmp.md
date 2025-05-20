# Function: <code>inetpeer_addr_cmp</code>

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
In net/ipv4/inetpeer.c (ffffffff8175830a)
Location: include/net/inetpeer.h:130
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81780d2f)
Location: include/net/inetpeer.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
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
In net/ipv4/inetpeer.c (ffffffff817c45be)
Location: include/net/inetpeer.h:130
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee508)
Location: include/net/inetpeer.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff817f40de)
Location: include/net/inetpeer.h:130
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181ef08)
Location: include/net/inetpeer.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff8181451f)
Location: include/net/inetpeer.h:130
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fb43)
Location: include/net/inetpeer.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff818935a1)
Location: include/net/inetpeer.h:124
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff818beee3)
Location: include/net/inetpeer.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff818e77d5)
Location: include/net/inetpeer.h:124
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914ab0)
Location: include/net/inetpeer.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81914685)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943260)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81976be7)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a781c)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff819ad577)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de89f)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81a97510)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb985)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81aa14d0)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7943)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81a8c420)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2add)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81b47402)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b814d9)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81cd456d)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1191f)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81e9483d)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed76df)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81ef300d)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36ac1)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81fb6f9d)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcbde)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffff800010c5d7a8)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92618)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (c0d6cca0)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (c0da0708)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (c000000000d5fd20)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (c000000000da1ed0)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffe0007c616c)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1ac8)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff8194d3e7)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e70f)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff81906ed7)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff819381cf)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff819b7bb7)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8edf)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
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
In net/ipv4/inetpeer.c (ffffffff819c1427)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2c3f)
Location: include/net/inetpeer.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics
```
</details>
</li>
</ul>

## Differences
