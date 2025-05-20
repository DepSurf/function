# Function: <code>dev_loopback_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719770)
Location: net/core/dev.c:2957
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81719770-ffffffff81719849: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781c50)
Location: net/core/dev.c:3157
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81781c50-ffffffff81781d2f: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af560)
Location: net/core/dev.c:3155
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff817af560-ffffffff817af63f: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cde70)
Location: net/core/dev.c:3235
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff817cde70-ffffffff817cdf04: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184ab40)
Location: net/core/dev.c:3281
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff8184ab40-ffffffff8184ac0a: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81894f20)
Location: net/core/dev.c:3324
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81894f20-ffffffff81894fe3: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5a00)
Location: net/core/dev.c:3568
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff818b5a00-ffffffff818b5aba: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3580
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff819073b6-ffffffff819073e1: dev_loopback_xmit.cold (STB_LOCAL)
ffffffff818ff360-ffffffff818ff420: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819316d0)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff819316d0-ffffffff81931772: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06e50)
Location: net/core/dev.c:3838
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a06e50-ffffffff81a06ef3: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a083d0)
Location: net/core/dev.c:3868
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a083d0-ffffffff81a08473: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eeb30)
Location: net/core/dev.c:3948
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff819eeb30-ffffffff819eebd3: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9fe50)
Location: net/core/dev.c:3912
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a9fe50-ffffffff81a9ff2f: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c15910)
Location: net/core/dev.c:3923
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81c15910-ffffffff81c159f3: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc6cd0)
Location: net/core/dev.c:3910
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81dc6cd0-ffffffff81dc6dc2: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e36070)
Location: net/core/dev.c:3870
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81e36070-ffffffff81e36176: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef4330)
Location: net/core/dev.c:3883
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81ef4330-ffffffff81ef4436: dev_loopback_xmit (STB_GLOBAL)
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
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcff68)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffff800010bcff68-ffff800010bd0088: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce8e20)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
c0ce8e20-c0ce8f18: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cacc80)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
c000000000cacc80-c000000000cacd94: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075a0a0)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffe00075a0a0-ffffffe00075a146: dev_loopback_xmit (STB_GLOBAL)
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
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d16d0)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff818d16d0-ffffffff818d1772: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b560)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff8188b560-ffffffff8188b602: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819226d0)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff819226d0-ffffffff81922772: dev_loopback_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_loopback_xmit(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819438a0)
Location: net/core/dev.c:3480
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff819438a0-ffffffff81943942: dev_loopback_xmit (STB_GLOBAL)
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
