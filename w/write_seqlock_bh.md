# Function: <code>write_seqlock_bh</code>

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
In net/core/neighbour.c (ffffffff81728848)
Location: include/linux/seqlock.h:455
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81757f8b)
Location: include/linux/seqlock.h:455
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817825e7)
Location: include/linux/seqlock.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1bb9)
Location: include/linux/seqlock.h:455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a55ec)
Location: include/linux/seqlock.h:455
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81792398)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817c423b)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817efaa7)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f879)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8181327c)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff817bfc68)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d5b)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff818204b3)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81840dc9)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8184478c)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff817de2fa)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8181413b)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff818409d0)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81862669)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81866144)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81858b5a)
Location: include/linux/seqlock.h:459
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff818936f8)
Location: include/linux/seqlock.h:459
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff818c0140)
Location: include/linux/seqlock.h:459
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2789)
Location: include/linux/seqlock.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6574)
Location: include/linux/seqlock.h:459
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff818a4496)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff818e7a53)
Location: include/linux/seqlock.h:458
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915c8f)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d0a0)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff818c79ff)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81914903)
Location: include/linux/seqlock.h:458
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194443f)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196cf30)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81914117)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81976d26)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8a07)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6830)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81946787)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819ad6b6)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df6e7)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d320)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81a16c0e)
Location: include/linux/seqlock.h:501
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a97646)
Location: include/linux/seqlock.h:501
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81accb4c)
Location: include/linux/seqlock.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe280)
Location: include/linux/seqlock.h:501
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81a16b21)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1612)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b4c)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c2f0)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff819fd79f)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c56c)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3bbc)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af9f50)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81aafdc3)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81b476ac)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8227c)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbad18)
Location: include/linux/seqlock.h:914
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81c28d57)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81cd48c5)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1275b)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4ee82)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81ddb9c1)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81e94ba5)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed857b)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18a82)
Location: include/linux/seqlock.h:910
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81e4c728)
Location: include/linux/seqlock.h:911
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81ef3375)
Location: include/linux/seqlock.h:911
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3768b)
Location: include/linux/seqlock.h:911
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f786e2)
Location: include/linux/seqlock.h:911
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81f0b43c)
Location: include/linux/seqlock.h:846
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7305)
Location: include/linux/seqlock.h:846
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd75b)
Location: include/linux/seqlock.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
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
In net/core/neighbour.c (ffff800010be6500)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffff800010c5da24)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c930a4)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc745c)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (c0cfeebc)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c0d6cdf0)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c0da1a68)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2308)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (c000000000cc8070)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c000000000d5ff48)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c000000000da3404)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3920)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffe00076b07c)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffe0007c62be)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f27c6)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b41a)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff818e6757)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8194d526)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f557)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad0c0)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff818a0597)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81907016)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81939017)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819696f0)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81937787)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819b7cf6)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9d27)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17960)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In net/core/neighbour.c (ffffffff81958f5e)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819c1579)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3b36)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22400)
Location: include/linux/seqlock.h:458
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
</details>
</li>
</ul>

## Differences
