# Function: <code>ndisc_send_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff817e0c70)
Location: net/ipv6/ndisc.c:1484
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff817e0c70-ffffffff817e1124: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184f560)
Location: net/ipv6/ndisc.c:1525
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff8184f560-ffffffff8184fa81: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818814b0)
Location: net/ipv6/ndisc.c:1545
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff818814b0-ffffffff818819aa: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a7500)
Location: net/ipv6/ndisc.c:1547
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff818a7500-ffffffff818a7ac7: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81929f70)
Location: net/ipv6/ndisc.c:1561
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81929f70-ffffffff8192a579: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1563
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81982a0b-ffffffff81982a17: ndisc_send_redirect.cold.42 (STB_LOCAL)
ffffffff81982280-ffffffff819827d2: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1563
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819b90ab-ffffffff819b90b7: ndisc_send_redirect.cold.42 (STB_LOCAL)
ffffffff819b8930-ffffffff819b8e7f: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1575
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81a27bb8-ffffffff81a27bc4: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81a273a0-ffffffff81a278e1: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81a5e618-ffffffff81a5e624: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81a5de00-ffffffff81a5e341: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1577
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81b573ee-ffffffff81b573fa: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81b56bd0-ffffffff81b5713d: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81c32eeb-ffffffff81c32ef7: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81b65240-ffffffff81b657ad: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1583
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81c251ec-ffffffff81c251f8: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81b53530-ffffffff81b53a57: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1588
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81d4060a-ffffffff81d40616: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81c1aa40-ffffffff81c1af91: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1636
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81f0cfd0-ffffffff81f0cfdc: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81db6fa0-ffffffff81db75b9: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f86c70)
Location: net/ipv6/ndisc.c:1656
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81f86c70-ffffffff81f8729a: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe6fb0)
Location: net/ipv6/ndisc.c:1657
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81fe6fb0-ffffffff81fe75da: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b4e10)
Location: net/ipv6/ndisc.c:1662
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff820b4e10-ffffffff820b5439: ndisc_send_redirect (STB_GLOBAL)
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
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d22ee8)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffff800010d22ee8-ffff800010d2338c: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c0e27504)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
c0e27504-c0e279b4: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e52da0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
c000000000e52da0-c000000000e53310: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe000864950)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffe000864950-ffffffe000864d2a: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819fdca8-ffffffff819fdcb4: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff819fd490-ffffffff819fd9d1: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819baa68-ffffffff819baa74: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff819ba250-ffffffff819ba791: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81a68728-ffffffff81a68734: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81a67f10-ffffffff81a68451: ndisc_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ndisc_send_redirect(struct sk_buff *skb, const struct in6_addr *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1576
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81a74d23-ffffffff81a74d2f: ndisc_send_redirect.cold (STB_LOCAL)
ffffffff81a74500-ffffffff81a74a41: ndisc_send_redirect (STB_GLOBAL)
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
