# Function: <code>tcp_v6_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff817f1aa0)
Location: net/ipv6/tcp_ipv6.c:1347
Inline: False
```
**Symbols:**

```
ffffffff817f1aa0-ffffffff817f2420: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81860320)
Location: net/ipv6/tcp_ipv6.c:1367
Inline: False
```
**Symbols:**

```
ffffffff81860320-ffffffff81860d8e: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818922b0)
Location: net/ipv6/tcp_ipv6.c:1383
Inline: False
```
**Symbols:**

```
ffffffff818922b0-ffffffff81892cb9: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b8910)
Location: net/ipv6/tcp_ipv6.c:1398
Inline: False
```
**Symbols:**

```
ffffffff818b8910-ffffffff818b9291: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8193b7b0)
Location: net/ipv6/tcp_ipv6.c:1408
Inline: False
```
**Symbols:**

```
ffffffff8193b7b0-ffffffff8193c1e7: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81994a00)
Location: net/ipv6/tcp_ipv6.c:1427
Inline: False
```
**Symbols:**

```
ffffffff81994a00-ffffffff819955c2: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819cb300)
Location: net/ipv6/tcp_ipv6.c:1431
Inline: False
```
**Symbols:**

```
ffffffff819cb300-ffffffff819cbea4: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a39d40)
Location: net/ipv6/tcp_ipv6.c:1457
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81a39d40-ffffffff81a3a9bc: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a708d0)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81a708d0-ffffffff81a7155f: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a070)
Location: net/ipv6/tcp_ipv6.c:1550
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81b6a070-ffffffff81b6ae43: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b78b50)
Location: net/ipv6/tcp_ipv6.c:1588
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81b78b50-ffffffff81b7990f: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b676a0)
Location: net/ipv6/tcp_ipv6.c:1618
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81b676a0-ffffffff81b68421: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1625
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81d40e8a-ffffffff81d40ef8: tcp_v6_rcv.cold (STB_LOCAL)
ffffffff81c2f2d0-ffffffff81c300eb: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1579
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81f0d7b6-ffffffff81f0d81c: tcp_v6_rcv.cold (STB_LOCAL)
ffffffff81dcc6e0-ffffffff81dcd4c1: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1589
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff820b4be6-ffffffff820b4c4c: tcp_v6_rcv.cold (STB_LOCAL)
ffffffff81f9d820-ffffffff81f9e5a8: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1587
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff82135ba4-ffffffff82135c03: tcp_v6_rcv.cold (STB_LOCAL)
ffffffff81ffe2a0-ffffffff81fff066: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:1747
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff8221781f-ffffffff8221786d: tcp_v6_rcv.cold (STB_LOCAL)
ffffffff820cd180-ffffffff820cdd7a: tcp_v6_rcv (STB_GLOBAL)
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
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d38da0)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
```
**Symbols:**

```
ffff800010d38da0-ffff800010d39988: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e3b950)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
```
**Symbols:**

```
c0e3b950-c0e3c478: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e6c260)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
```
**Symbols:**

```
c000000000e6c260-c000000000e6d070: tcp_v6_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe0008761a2)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
```
**Symbols:**

```
ffffffe0008761a2-ffffffe000876c1c: tcp_v6_rcv (STB_LOCAL)
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
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ff60)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81a0ff60-ffffffff81a10bef: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819ccd20)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff819ccd20-ffffffff819cd9af: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a9e0)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81a7a9e0-ffffffff81a7b66f: tcp_v6_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_v6_rcv(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a87220)
Location: net/ipv6/tcp_ipv6.c:1479
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
**Symbols:**

```
ffffffff81a87220-ffffffff81a87ebe: tcp_v6_rcv (STB_GLOBAL)
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
