# Function: <code>ipv4_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81756b30)
Location: net/ipv4/route.c:1005
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81756b30-ffffffff81756c18: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c2dd0)
Location: net/ipv4/route.c:1011
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff817c2dd0-ffffffff817c2eb8: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1490)
Location: net/ipv4/route.c:1017
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff817f1490-ffffffff817f15a9: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81812d50)
Location: net/ipv4/route.c:1035
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81812d50-ffffffff81812e61: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81892390)
Location: net/ipv4/route.c:1042
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81892390-ffffffff818924a1: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e6370)
Location: net/ipv4/route.c:1042
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff818e6370-ffffffff818e6476: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81913290)
Location: net/ipv4/route.c:1046
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81913290-ffffffff81913387: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81975810)
Location: net/ipv4/route.c:1055
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81975810-ffffffff8197590f: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ac220)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819ac220-ffffffff819ac31f: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a96020)
Location: net/ipv4/route.c:1061
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81a96020-ffffffff81a96125: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa00c0)
Location: net/ipv4/route.c:1067
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81aa00c0-ffffffff81aa01c5: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8b000)
Location: net/ipv4/route.c:1051
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81a8b000-ffffffff81a8b102: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b45f40)
Location: net/ipv4/route.c:1066
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81b45f40-ffffffff81b46042: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2d00)
Location: net/ipv4/route.c:1073
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81cd2d00-ffffffff81cd2e2c: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e92ff0)
Location: net/ipv4/route.c:1073
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81e92ff0-ffffffff81e9311c: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef1790)
Location: net/ipv4/route.c:1073
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81ef1790-ffffffff81ef18bc: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb58e0)
Location: net/ipv4/route.c:1073
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81fb58e0-ffffffff81fb5a0c: ipv4_update_pmtu (STB_GLOBAL)
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
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5c2d8)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffff800010c5c2d8-ffff800010c5c3d8: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6b9f8)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
c0d6b9f8-c0d6bb00: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5e690)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
c000000000d5e690-c000000000d5e7dc: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c531e)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffe0007c531e-ffffffe0007c53f6: ipv4_update_pmtu (STB_GLOBAL)
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
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194c090)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff8194c090-ffffffff8194c18f: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81905b80)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81905b80-ffffffff81905c7f: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b6860)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819b6860-ffffffff819b695f: ipv4_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv4_update_pmtu(struct sk_buff *skb, struct net *net, u32 mtu, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819c00d0)
Location: net/ipv4/route.c:1057
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819c00d0-ffffffff819c01cf: ipv4_update_pmtu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 mark</code>
</li>
<li>
<b>Param removed. </b>
<code>int flow_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, net, mtu, oif, mark, protocol, flow_flags</code> ➡️ <code>skb, net, mtu, oif, protocol</code>
</li>
</ul>
</details>
</li>
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
