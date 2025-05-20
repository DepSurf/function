# Function: <code>ip6_rcv_core</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81999030)
Location: net/ipv6/ip6_input.c:121
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81999030-ffffffff81999479: ip6_rcv_core.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a04f30)
Location: net/ipv6/ip6_input.c:121
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81a04f30-ffffffff81a053a3: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a3bb00)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81a3bb00-ffffffff81a3bf88: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b30f80)
Location: net/ipv6/ip6_input.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81b30f80-ffffffff81b3143a: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b3fbb0)
Location: net/ipv6/ip6_input.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81b3fbb0-ffffffff81b40041: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b2d9e0)
Location: net/ipv6/ip6_input.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81b2d9e0-ffffffff81b2de81: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81bf3c30)
Location: net/ipv6/ip6_input.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81bf3c30-ffffffff81bf416b: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81d8c950)
Location: net/ipv6/ip6_input.c:148
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81d8c950-ffffffff81d8cf0e: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81f5ab60)
Location: net/ipv6/ip6_input.c:148
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81f5ab60-ffffffff81f5b11e: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81fba910)
Location: net/ipv6/ip6_input.c:148
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81fba910-ffffffff81fbaee7: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff82087d40)
Location: net/ipv6/ip6_input.c:149
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff82087d40-ffffffff820882f9: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffff800010cfd088)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffff800010cfd088-ffff800010cfd568: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c0e041c0)
Location: net/ipv6/ip6_input.c:123
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
c0e041c0-c0e04a64: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c000000000e24b20)
Location: net/ipv6/ip6_input.c:123
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
c000000000e24b20-c000000000e25124: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip6_rcv_core(struct sk_buff *skb, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffe00084743a)
Location: net/ipv6/ip6_input.c:123
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffe00084743a-ffffffe0008478d0: ip6_rcv_core (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819db190)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff819db190-ffffffff819db618: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81997f50)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81997f50-ffffffff819983d8: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a45c10)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81a45c10-ffffffff81a46098: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a518e0)
Location: net/ipv6/ip6_input.c:123
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
**Symbols:**

```
ffffffff81a518e0-ffffffff81a51d7f: ip6_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
