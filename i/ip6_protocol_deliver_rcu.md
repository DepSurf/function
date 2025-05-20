# Function: <code>ip6_protocol_deliver_rcu</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81999a00)
Location: net/ipv6/ip6_input.c:322
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input
```
**Symbols:**

```
ffffffff81999a00-ffffffff81999ec6: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a05930)
Location: net/ipv6/ip6_input.c:325
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81a05930-ffffffff81a05e20: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a3c4b0)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81a3c4b0-ffffffff81a3c984: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b31b50)
Location: net/ipv6/ip6_input.c:361
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input
```
**Symbols:**

```
ffffffff81b31b50-ffffffff81b32026: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b40750)
Location: net/ipv6/ip6_input.c:351
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input
```
**Symbols:**

```
ffffffff81b40750-ffffffff81b40c2d: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b2dfe0)
Location: net/ipv6/ip6_input.c:350
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input
```
**Symbols:**

```
ffffffff81b2dfe0-ffffffff81b2e4c8: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81bf42c0)
Location: net/ipv6/ip6_input.c:350
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input
```
**Symbols:**

```
ffffffff81bf42c0-ffffffff81bf47e4: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81d8cfd0)
Location: net/ipv6/ip6_input.c:362
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81d8cfd0-ffffffff81d8d56d: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81f5b130)
Location: net/ipv6/ip6_input.c:362
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81f5b130-ffffffff81f5b637: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81fbaf00)
Location: net/ipv6/ip6_input.c:362
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81fbaf00-ffffffff81fbb40f: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff82088310)
Location: net/ipv6/ip6_input.c:363
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff82088310-ffffffff8208881f: ip6_protocol_deliver_rcu (STB_GLOBAL)
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
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffff800010cfd780)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffff800010cfd780-ffff800010cfdca8: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c0e04f84)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
c0e04f84-c0e05728: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c000000000e25840)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
c000000000e25840-c000000000e25f00: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffe000847cd6)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffe000847cd6-ffffffe000848162: ip6_protocol_deliver_rcu (STB_GLOBAL)
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
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819dbb40)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff819dbb40-ffffffff819dc014: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81998900)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81998900-ffffffff81998dd4: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a465c0)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81a465c0-ffffffff81a46a94: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int nexthdr, bool have_final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a522f0)
Location: net/ipv6/ip6_input.c:337
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
**Symbols:**

```
ffffffff81a522f0-ffffffff81a527c4: ip6_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
