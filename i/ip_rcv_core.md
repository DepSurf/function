# Function: <code>ip_rcv_core</code>

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
In net/ipv4/ip_input.c (ffffffff819150e0)
Location: net/ipv4/ip_input.c:421
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819150e0-ffffffff81915368: ip_rcv_core.isra.25 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff819775f0)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819775f0-ffffffff81977896: ip_rcv_core.isra.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff819adf80)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819adf80-ffffffff819ae226: ip_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a97e20)
Location: net/ipv4/ip_input.c:435
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81a97e20-ffffffff81a98104: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa1d80)
Location: net/ipv4/ip_input.c:435
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81aa1d80-ffffffff81aa205d: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8ccb0)
Location: net/ipv4/ip_input.c:436
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81a8ccb0-ffffffff81a8cf88: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b47de0)
Location: net/ipv4/ip_input.c:436
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81b47de0-ffffffff81b48105: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5050)
Location: net/ipv4/ip_input.c:451
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81cd5050-ffffffff81cd53a4: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e95520)
Location: net/ipv4/ip_input.c:456
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81e95520-ffffffff81e95874: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef3d20)
Location: net/ipv4/ip_input.c:456
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81ef3d20-ffffffff81ef40c0: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb7cb0)
Location: net/ipv4/ip_input.c:456
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81fb7cb0-ffffffff81fb8040: ip_rcv_core (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffff800010c5dfa8)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffff800010c5dfa8-ffff800010c5e2d4: ip_rcv_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6d86c)
Location: net/ipv4/ip_input.c:420
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
c0d6d86c-c0d6dd78: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d60bc0)
Location: net/ipv4/ip_input.c:420
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
c000000000d60bc0-c000000000d60fac: ip_rcv_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip_rcv_core(struct sk_buff *skb, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c6b56)
Location: net/ipv4/ip_input.c:420
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffe0007c6b56-ffffffe0007c6e04: ip_rcv_core (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff8194ddf0)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff8194ddf0-ffffffff8194e096: ip_rcv_core.isra.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff819078e0)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819078e0-ffffffff81907b86: ip_rcv_core.isra.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff819b85c0)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819b85c0-ffffffff819b8866: ip_rcv_core.isra.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff819c1e20)
Location: net/ipv4/ip_input.c:420
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819c1e20-ffffffff819c20c6: ip_rcv_core.isra.0 (STB_LOCAL)
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
