# Function: <code>ipmr_rt_fib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1923
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1899
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1910
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1952
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e9234)
Location: net/ipv4/ipmr.c:2114
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8193fd36)
Location: net/ipv4/ipmr.c:2044
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196f5d0)
Location: net/ipv4/ipmr.c:2057
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819d8d13)
Location: net/ipv4/ipmr.c:2069
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0f0c0)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81a0f0c0-ffffffff81a0f178: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b00070)
Location: net/ipv4/ipmr.c:2037
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81b00070-ffffffff81b00128: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0e0b0)
Location: net/ipv4/ipmr.c:2044
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81b0e0b0-ffffffff81b0e168: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afbeb0)
Location: net/ipv4/ipmr.c:2044
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81afbeb0-ffffffff81afbf62: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbd350)
Location: net/ipv4/ipmr.c:2046
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81bbd350-ffffffff81bbd402: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d51af0)
Location: net/ipv4/ipmr.c:2040
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81d51af0-ffffffff81d51bbe: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1ba60)
Location: net/ipv4/ipmr.c:2061
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81f1ba60-ffffffff81f1bb2e: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7b520)
Location: net/ipv4/ipmr.c:2076
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81f7b520-ffffffff81f7b5f1: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82041c10)
Location: net/ipv4/ipmr.c:2074
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff82041c10-ffffffff82041ce1: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cc8fc8)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffff800010cc8fc8-ffff800010cc90a0: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd43c8)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
c0dd43c8-c0dd44a4: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de6550)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
c000000000de6550-c000000000de6640: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081d1de)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffe00081d1de-ffffffe00081d27a: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819af4a3)
Location: net/ipv4/ipmr.c:2069
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196bad3)
Location: net/ipv4/ipmr.c:2069
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a19d43)
Location: net/ipv4/ipmr.c:2069
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mr_table *ipmr_rt_fib_lookup(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a24160)
Location: net/ipv4/ipmr.c:2069
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff81a24160-ffffffff81a24218: ipmr_rt_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
