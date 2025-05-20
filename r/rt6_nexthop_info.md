# Function: <code>rt6_nexthop_info</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt6_nexthop_info(struct sk_buff *skb, struct rt6_info *rt, unsigned int *flags, bool skip_oif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897ec0)
Location: net/ipv6/route.c:3326
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff81897ec0-ffffffff81897fd0: rt6_nexthop_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt6_nexthop_info(struct sk_buff *skb, struct rt6_info *rt, unsigned int *flags, bool skip_oif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81919240)
Location: net/ipv6/route.c:4013
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff81919240-ffffffff81919373: rt6_nexthop_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt6_nexthop_info(struct sk_buff *skb, struct fib6_info *rt, unsigned int *flags, bool skip_oif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81970d20)
Location: net/ipv6/route.c:4598
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff81970d20-ffffffff81970e65: rt6_nexthop_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt6_nexthop_info(struct sk_buff *skb, struct fib6_info *rt, unsigned int *flags, bool skip_oif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6950)
Location: net/ipv6/route.c:4571
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff819a6950-ffffffff819a6a95: rt6_nexthop_info (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
