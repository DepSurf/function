# Function: <code>dst_check</code>

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
In net/ipv4/route.c (ffffffff81756fb2)
Location: include/net/dst.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e2e5)
Location: include/net/dst.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8178aa0f)
Location: include/net/dst.h:501
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b2cd5)
Location: include/net/dst.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0541)
Location: include/net/dst.h:501
Inline: True
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
In net/ipv4/route.c (ffffffff817c3250)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb735)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff817f8051)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181fdc7)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f399)
Location: include/net/dst.h:510
Inline: True
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
In net/ipv4/route.c (ffffffff817f1977)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c0a5)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81828ef1)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851627)
Location: include/net/dst.h:510
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818913b9)
Location: include/net/dst.h:510
Inline: True
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
In net/ipv4/route.c (ffffffff8181324d)
Location: include/net/dst.h:480
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c873)
Location: include/net/dst.h:480
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8184a324)
Location: include/net/dst.h:480
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187386c)
Location: include/net/dst.h:480
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff818aa2fe)
Location: include/net/dst.h:480
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b79b7)
Location: include/net/dst.h:480
Inline: True
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
In net/ipv4/route.c (ffffffff81892893)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbfb4)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff818c9ec6)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f41c8)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff8192cdb8)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a80d)
Location: include/net/dst.h:469
Inline: True
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
In net/ipv4/route.c (ffffffff818e683b)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911986)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8191fe79)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ac45)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81985515)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819936bd)
Location: include/net/dst.h:453
Inline: True
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
In net/ipv4/route.c (ffffffff81913693)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940170)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8194ead7)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d6b6)
Location: include/net/dst.h:453
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bbc85)
Location: include/net/dst.h:453
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9a87)
Location: include/net/dst.h:453
Inline: True
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
In net/ipv4/route.c (ffffffff81975cdf)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4684)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819b32aa)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6af6)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a919)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3851d)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff819ac6ef)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db384)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819ea02d)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1dae6)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6146c)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f06d)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff81a96bcf)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8414)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ad7c73)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f1b4)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81b5a74d)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67211)
Location: include/net/dst.h:452
Inline: True
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
In net/ipv4/route.c (ffffffff81aa0caa)
Location: include/net/dst.h:450
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad43b4)
Location: include/net/dst.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ae42c3)
Location: include/net/dst.h:450
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d4a4)
Location: include/net/dst.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81b68e4d)
Location: include/net/dst.h:450
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75799)
Location: include/net/dst.h:450
Inline: True
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
In net/ipv4/route.c (ffffffff81a8bbda)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf454)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81acf45a)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0be0c)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81b56f85)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b641cd)
Location: include/net/dst.h:466
Inline: True
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
In net/ipv4/route.c (ffffffff81b46b6a)
Location: include/net/dst.h:468
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7cfa1)
Location: include/net/dst.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81b8de7a)
Location: include/net/dst.h:468
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcedcc)
Location: include/net/dst.h:468
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81c1d18d)
Location: include/net/dst.h:468
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c83a)
Location: include/net/dst.h:468
Inline: True
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
In net/ipv4/route.c (ffffffff81cd3c1f)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cee1)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81d1f0c3)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d64d9c)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81dbbd0d)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd6ed)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
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
In net/ipv4/route.c (ffffffff81e93e4f)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2958)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ee61db)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2fc3c)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81f8be35)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e7fd)
Location: include/net/dst.h:462
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
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
In net/ipv4/route.c (ffffffff81ef25eb)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31634)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81f459d3)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f906cc)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff81fec5cd)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff2b9)
Location: include/net/dst.h:476
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
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
In net/ipv4/route.c (ffffffff81fb6706)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7824)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8200bb23)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e42f)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/udp.c (ffffffff820ba1dd)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdfc9)
Location: include/net/dst.h:469
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
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
In net/ipv4/route.c (ffff800010c5c8c0)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e76c)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffff800010c9f824)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda094)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d24648)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36abc)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (c0d6bf50)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (c0d9d6c8)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (c0dacb44)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (c0de3dcc)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (c0e2b4e4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (c0e3a78c)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (c000000000d5ecc4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d108)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (c000000000db2328)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb090)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (c000000000e56f20)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6a2b8)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffe0007c56fc)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeab8)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffe0007fc372)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c51a)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffe0008681f6)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008752c0)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff8194c55f)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b1f4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81989e9d)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd176)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a00afc)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e6fd)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff8190604f)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934cb4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8194395d)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979f66)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bd8bc)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb4bd)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff819b6d2f)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e59c4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819f466d)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27bf6)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6b57c)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7917d)
Location: include/net/dst.h:445
Inline: True
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
In net/ipv4/route.c (ffffffff819c05b2)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef684)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819fe82d)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33226)
Location: include/net/dst.h:445
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a77b8c)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8593d)
Location: include/net/dst.h:445
Inline: True
```
</details>
</li>
</ul>

## Differences
