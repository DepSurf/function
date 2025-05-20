# Function: <code>write_sequnlock_bh</code>

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
In net/core/neighbour.c (ffffffff8172887f)
Location: include/linux/seqlock.h:461
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81757fc9)
Location: include/linux/seqlock.h:461
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff81782654)
Location: include/linux/seqlock.h:461
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1be1)
Location: include/linux/seqlock.h:461
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5616)
Location: include/linux/seqlock.h:461
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
In net/core/neighbour.c (ffffffff817923d5)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817c4279)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817efb14)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f8a1)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818132a6)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff817bfca5)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d99)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff8182051f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81840df1)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818447b6)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff817de332)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81814179)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840a38)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81862691)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8186616e)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff81858b94)
Location: include/linux/seqlock.h:465
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81893812)
Location: include/linux/seqlock.h:465
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff818c01a8)
Location: include/linux/seqlock.h:465
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff818e27b1)
Location: include/linux/seqlock.h:465
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e659e)
Location: include/linux/seqlock.h:465
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
In net/core/neighbour.c (ffffffff818a44c0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff818e7abf)
Location: include/linux/seqlock.h:464
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915cf7)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d0ca)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff818c7a25)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8191496f)
Location: include/linux/seqlock.h:464
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819444a7)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196cf5a)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff8191413d)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81976d90)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8a6f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d685a)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff819467ad)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819ad720)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df74f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d34a)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff81a16c36)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a976b7)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81accb97)
Location: include/linux/seqlock.h:507
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe2aa)
Location: include/linux/seqlock.h:507
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
In net/core/neighbour.c (ffffffff81a16b48)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1678)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b97)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c31a)
Location: include/linux/seqlock.h:928
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
In net/core/neighbour.c (ffffffff819fd7c3)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c5d8)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3c07)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af9f7a)
Location: include/linux/seqlock.h:928
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
In net/core/neighbour.c (ffffffff81aafdea)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81b47718)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b822c7)
Location: include/linux/seqlock.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbad51)
Location: include/linux/seqlock.h:928
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
In net/core/neighbour.c (ffffffff81c28d86)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81cd492f)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d127cf)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4eebb)
Location: include/linux/seqlock.h:924
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
In net/core/neighbour.c (ffffffff81ddb9f0)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81e94c0f)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed85ef)
Location: include/linux/seqlock.h:924
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18abb)
Location: include/linux/seqlock.h:924
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
In net/core/neighbour.c (ffffffff81e4c754)
Location: include/linux/seqlock.h:925
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81ef33df)
Location: include/linux/seqlock.h:925
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f376ff)
Location: include/linux/seqlock.h:925
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f7871b)
Location: include/linux/seqlock.h:925
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
In net/core/neighbour.c (ffffffff81f0b468)
Location: include/linux/seqlock.h:860
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81fb736f)
Location: include/linux/seqlock.h:860
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd7cf)
Location: include/linux/seqlock.h:860
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
In net/core/neighbour.c (ffff800010be6560)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffff800010c5daa4)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9313c)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc74b8)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (c0cfeeec)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c0d6ce64)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c0da1ae4)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd234c)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (c000000000cc80ac)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c000000000d5ffb0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c000000000da34a0)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de396c)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffe00076b0a8)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffe0007c6308)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2834)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b454)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff818e677d)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8194d590)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f5bf)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad0ea)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff818a05bd)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81907080)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8193907f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196971a)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff819377ad)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819b7d60)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9d8f)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a1798a)
Location: include/linux/seqlock.h:464
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
In net/core/neighbour.c (ffffffff81958f8b)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819c15e5)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3ba9)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a2242a)
Location: include/linux/seqlock.h:464
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
</details>
</li>
</ul>

## Differences
