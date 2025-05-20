# Function: <code>tcp_synq_no_recent_overflow</code>

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
In net/ipv4/syncookies.c (ffffffff817ab476)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817ff344)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff81818f71)
Location: include/net/tcp.h:503
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8186ecb1)
Location: include/net/tcp.h:503
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff8184a7d1)
Location: include/net/tcp.h:501
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818a1c01)
Location: include/net/tcp.h:501
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff8186e170)
Location: include/net/tcp.h:507
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818c81cb)
Location: include/net/tcp.h:507
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff818eeb00)
Location: include/net/tcp.h:478
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8194b77b)
Location: include/net/tcp.h:478
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff8194540f)
Location: include/net/tcp.h:484
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819a4a25)
Location: include/net/tcp.h:484
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff819757a2)
Location: include/net/tcp.h:498
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819db538)
Location: include/net/tcp.h:498
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff8192490e)
Location: include/net/tcp.h:499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff819df2bf)
Location: include/net/tcp.h:499
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a4a1a6)
Location: include/net/tcp.h:499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81956c1e)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81a16350)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a80d66)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81a2a5ee)
Location: include/net/tcp.h:516
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81b07370)
Location: include/net/tcp.h:516
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b7b9e5)
Location: include/net/tcp.h:516
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81a2b137)
Location: include/net/tcp.h:521
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81b1573e)
Location: include/net/tcp.h:521
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b8aa25)
Location: include/net/tcp.h:521
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81a1244e)
Location: include/net/tcp.h:522
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81b0355b)
Location: include/net/tcp.h:522
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b79897)
Location: include/net/tcp.h:522
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81ac311e)
Location: include/net/tcp.h:515
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81bc57eb)
Location: include/net/tcp.h:515
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81c44541)
Location: include/net/tcp.h:515
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81c3dea6)
Location: include/net/tcp.h:526
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81d5aa21)
Location: include/net/tcp.h:526
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81de3530)
Location: include/net/tcp.h:526
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81df2076)
Location: include/net/tcp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81f24e91)
Location: include/net/tcp.h:536
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81fb5bb0)
Location: include/net/tcp.h:536
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81e64006)
Location: include/net/tcp.h:530
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81f84a21)
Location: include/net/tcp.h:530
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff820162c1)
Location: include/net/tcp.h:530
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81f231d6)
Location: include/net/tcp.h:542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff8204b2aa)
Location: include/net/tcp.h:542
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff820e5401)
Location: include/net/tcp.h:542
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffff800010bf83c8)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffff800010cd2060)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffff800010d4c5e0)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (c0d12030)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (c0ddbee4)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c0e4d880)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (c000000000cdf140)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (c000000000df0440)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c000000000e82ca0)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffe00077a0e0)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffe000823418)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffe000885332)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff818f6bee)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff819b59e0)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a203f6)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff818b0a1e)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff819727d0)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819dd1b6)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff81947c1e)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81a20280)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a8ae76)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/filter.c (ffffffff8196952e)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
```
```
In net/ipv4/syncookies.c (ffffffff81a2b780)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a97ad6)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>

## Differences
