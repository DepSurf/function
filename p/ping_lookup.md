# Function: <code>ping_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff817a2320)
Location: net/ipv4/ping.c:171
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_rcv
```
**Symbols:**

```
ffffffff817a2320-ffffffff817a2593: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81811730)
Location: net/ipv4/ping.c:173
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81811730-ffffffff81811972: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81842c40)
Location: net/ipv4/ping.c:173
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81842c40-ffffffff81842e82: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818644c0)
Location: net/ipv4/ping.c:174
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff818644c0-ffffffff818646f6: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818e4600)
Location: net/ipv4/ping.c:174
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff818e4600-ffffffff818e4840: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff8193aec0)
Location: net/ipv4/ping.c:174
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff8193aec0-ffffffff8193b0f8: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff8196abb0)
Location: net/ipv4/ping.c:174
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff8196abb0-ffffffff8196ade9: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819d1870)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819d1870-ffffffff819d1ab4: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a083d0)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81a083d0-ffffffff81a08617: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af8020)
Location: net/ipv4/ping.c:169
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81af8020-ffffffff81af8288: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81b04e80)
Location: net/ipv4/ping.c:169
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81b04e80-ffffffff81b050e8: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af06e0)
Location: net/ipv4/ping.c:169
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81af06e0-ffffffff81af0942: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81bb04b0)
Location: net/ipv4/ping.c:169
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81bb04b0-ffffffff81bb07ba: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81d43ad0)
Location: net/ipv4/ping.c:170
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81d43ad0-ffffffff81d43d70: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f0cb20)
Location: net/ipv4/ping.c:176
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81f0cb20-ffffffff81f0cdb9: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f6c790)
Location: net/ipv4/ping.c:167
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81f6c790-ffffffff81f6ca2b: ping_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ping.c (ffffffff82032ee0)
Location: net/ipv4/ping.c:167
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff82032ee0-ffffffff8203317b: ping_lookup.isra.0 (STB_LOCAL)
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
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffff800010cc15c8)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffff800010cc15c8-ffff800010cc18e8: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c0dcb720)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
c0dcb720-c0dcb9f0: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c000000000ddc960)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
c000000000ddc960-c000000000ddcd38: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffe0008159d0)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffe0008159d0-ffffffe000815c5c: ping_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819a8170)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819a8170-ffffffff819a83b7: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81961c30)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81961c30-ffffffff81961e77: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a12a10)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81a12a10-ffffffff81a12c57: ping_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *ping_lookup(struct net *net, struct sk_buff *skb, u16 ident);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a1d3e0)
Location: net/ipv4/ping.c:169
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81a1d3e0-ffffffff81a1d627: ping_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
