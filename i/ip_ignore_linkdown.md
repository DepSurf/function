# Function: <code>ip_ignore_linkdown</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ca935)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff819cd0fa)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff81a01525)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a03c53)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff81af0572)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81af38d7)
Location: include/linux/inetdevice.h:240
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
In net/ipv4/fib_semantics.c (ffffffff81afd539)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81b007f0)
Location: include/linux/inetdevice.h:240
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
In net/ipv4/fib_semantics.c (ffffffff81ae8d3a)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81aebe77)
Location: include/linux/inetdevice.h:240
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
In net/ipv4/fib_semantics.c (ffffffff81ba8d58)
Location: include/linux/inetdevice.h:249
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81bac090)
Location: include/linux/inetdevice.h:249
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
In net/ipv4/fib_semantics.c (ffffffff81d3b7b7)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81d3eeee)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/ipv4/fib_semantics.c (ffffffff81f04187)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81f07ace)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/ipv4/fib_semantics.c (ffffffff81f63b67)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81f675ae)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/ipv4/fib_semantics.c (ffffffff8202a137)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff8202db8e)
Location: include/linux/inetdevice.h:254
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
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
In net/ipv4/fib_semantics.c (ffff800010cb9bac)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffff800010cbc840)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (c0dc5384)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (c0dc8010)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (c000000000dd2cac)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (c000000000dd64c8)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffe0008106ec)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffe000812c32)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff819a12c5)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff819a39f3)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff8195ad85)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff8195d4b3)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff81a0bb65)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a0e293)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
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
In net/ipv4/fib_semantics.c (ffffffff81a16355)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a18aa3)
Location: include/linux/inetdevice.h:240
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
</details>
</li>
</ul>

## Differences
