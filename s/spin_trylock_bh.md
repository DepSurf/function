# Function: <code>spin_trylock_bh</code>

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
In kernel/padata.c (ffffffff81189bc6)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff817dc045)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8119c2b6)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff8184a027)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff811ac0a6)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff8187beb7)
Location: include/linux/spinlock.h:365
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff811b36e6)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff818a185d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff811c7356)
Location: include/linux/spinlock.h:368
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff819241cd)
Location: include/linux/spinlock.h:368
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff811e75c0)
Location: include/linux/spinlock.h:368
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c5d5)
Location: include/linux/spinlock.h:368
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff811f84e0)
Location: include/linux/spinlock.h:387
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff818a7af3)
Location: include/linux/spinlock.h:387
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff819b22ec)
Location: include/linux/spinlock.h:387
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8120ffd0)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff818f37c9)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff81a20760)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8121e13f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff81925779)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff81a573c0)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8124a64f)
Location: include/linux/spinlock.h:411
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4f520)
Location: include/linux/spinlock.h:411
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/mptcp/protocol.c (ffffffff81baba4d)
Location: include/linux/spinlock.h:411
Inline: True
Inline callers:
  - net/mptcp/protocol.c:move_skbs_to_msk
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
In kernel/padata.c (ffffffff812549ff)
Location: include/linux/spinlock.h:412
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5e1a0)
Location: include/linux/spinlock.h:412
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff81258faf)
Location: include/linux/spinlock.h:412
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c420)
Location: include/linux/spinlock.h:412
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff81294c4f)
Location: include/linux/spinlock.h:421
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81c13730)
Location: include/linux/spinlock.h:421
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff812e96af)
Location: include/linux/spinlock.h:407
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81daed8d)
Location: include/linux/spinlock.h:407
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8135347f)
Location: include/linux/spinlock.h:408
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e8fd)
Location: include/linux/spinlock.h:408
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8138467f)
Location: include/linux/spinlock.h:409
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdeb06)
Location: include/linux/spinlock.h:409
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff813ada8f)
Location: include/linux/spinlock.h:409
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/ipv6/ip6_fib.c (ffffffff820ac686)
Location: include/linux/spinlock.h:409
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffff8000102a9d18)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffff800010bc19a8)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffff800010d1c05c)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (c04d7acc)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (c0cdc90c)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (c0e21484)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (c00000000035c7fc)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (c000000000c9a8ac)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (c000000000e4aa00)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffe0001d328c)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffe00074e460)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffe00085fed8)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8121678f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff818c5779)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff819f6a50)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff812094ef)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff8187f6b9)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff819b3810)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8121452f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff81916779)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff81a614d0)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
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
In kernel/padata.c (ffffffff8122256f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In net/core/net_namespace.c (ffffffff81937979)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6d990)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
</details>
</li>
</ul>

## Differences
