# Function: <code>ipv4_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81756c20)
Location: net/ipv4/route.c:1096
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81756c20-ffffffff81756ce8: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c2ec0)
Location: net/ipv4/route.c:1102
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff817c2ec0-ffffffff817c2f88: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1670)
Location: net/ipv4/route.c:1109
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff817f1670-ffffffff817f1772: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81812f20)
Location: net/ipv4/route.c:1127
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81812f20-ffffffff8181301a: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81892560)
Location: net/ipv4/route.c:1134
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81892560-ffffffff8189265a: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, u8 protocol, int flow_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e6530)
Location: net/ipv4/route.c:1134
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff818e6530-ffffffff818e6620: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81913390)
Location: net/ipv4/route.c:1136
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81913390-ffffffff81913470: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819759c0)
Location: net/ipv4/route.c:1145
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819759c0-ffffffff81975aa1: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ac3d0)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819ac3d0-ffffffff819ac4b1: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a96290)
Location: net/ipv4/route.c:1151
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81a96290-ffffffff81a9637b: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa0330)
Location: net/ipv4/route.c:1157
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81aa0330-ffffffff81aa041b: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8b270)
Location: net/ipv4/route.c:1141
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81a8b270-ffffffff81a8b35b: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b461b0)
Location: net/ipv4/route.c:1156
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81b461b0-ffffffff81b4629b: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2fb0)
Location: net/ipv4/route.c:1163
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81cd2fb0-ffffffff81cd30c4: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e93220)
Location: net/ipv4/route.c:1163
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81e93220-ffffffff81e93334: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef19c0)
Location: net/ipv4/route.c:1163
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81ef19c0-ffffffff81ef1ad4: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb5b10)
Location: net/ipv4/route.c:1163
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81fb5b10-ffffffff81fb5c24: ipv4_redirect (STB_GLOBAL)
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
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5c4b8)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffff800010c5c4b8-ffff800010c5c5a8: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6bbd0)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
c0d6bbd0-c0d6bcd0: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5e8e0)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
c000000000d5e8e0-c000000000d5ea10: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c548e)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffe0007c548e-ffffffe0007c5556: ipv4_redirect (STB_GLOBAL)
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
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194c240)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff8194c240-ffffffff8194c321: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81905d30)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff81905d30-ffffffff81905e11: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b6a10)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819b6a10-ffffffff819b6af1: ipv4_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv4_redirect(struct sk_buff *skb, struct net *net, int oif, u8 protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819c0280)
Location: net/ipv4/route.c:1147
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_err
```
**Symbols:**

```
ffffffff819c0280-ffffffff819c0361: ipv4_redirect (STB_GLOBAL)
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
<code>skb, net, oif, mark, protocol, flow_flags</code> ➡️ <code>skb, net, oif, protocol</code>
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
