# Function: <code>inet_gro_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81793490)
Location: net/ipv4/af_inet.c:1397
Inline: False
```
**Symbols:**

```
ffffffff81793490-ffffffff81793536: inet_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81800a40)
Location: net/ipv4/af_inet.c:1453
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81800a40-ffffffff81800af5: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81831980)
Location: net/ipv4/af_inet.c:1465
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81831980-ffffffff81831a4a: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81852f10)
Location: net/ipv4/af_inet.c:1486
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81852f10-ffffffff81852fca: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d2d50)
Location: net/ipv4/af_inet.c:1490
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff818d2d50-ffffffff818d2e0e: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81929310)
Location: net/ipv4/af_inet.c:1559
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81929310-ffffffff819293ce: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81958f50)
Location: net/ipv4/af_inet.c:1566
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81958f50-ffffffff81959029: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff819bf6ad-ffffffff819bf6c5: inet_gro_complete.cold (STB_LOCAL)
ffffffff819bda20-ffffffff819bdaf3: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f4630)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff819f4630-ffffffff819f4703: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae2340)
Location: net/ipv4/af_inet.c:1613
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81ae2340-ffffffff81ae2413: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aef1c0)
Location: net/ipv4/af_inet.c:1605
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81aef1c0-ffffffff81aef2bf: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ada920)
Location: net/ipv4/af_inet.c:1607
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81ada920-ffffffff81adaa0d: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b99b60)
Location: net/ipv4/af_inet.c:1612
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81b99b60-ffffffff81b99c4d: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2bb00)
Location: net/ipv4/af_inet.c:1603
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81d2bb00-ffffffff81d2bc0e: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef3710)
Location: net/ipv4/af_inet.c:1620
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81ef3710-ffffffff81ef381e: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f531a0)
Location: net/ipv4/af_inet.c:1620
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81f531a0-ffffffff81f532c9: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff82019550)
Location: net/ipv4/af_inet.c:1643
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff82019550-ffffffff82019679: inet_gro_complete (STB_GLOBAL)
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
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010ca9fc0)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffff800010ca9fc0-ffff800010caa0a8: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db6880)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
c0db6880-c0db6970: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dbf830)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
c000000000dbf830-c000000000dbf94c: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe000804aee)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffe000804aee-ffffffe000804bca: inet_gro_complete (STB_GLOBAL)
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
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819943d0)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff819943d0-ffffffff819944a3: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194de90)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff8194de90-ffffffff8194df63: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fec70)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff819fec70-ffffffff819fed43: inet_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a08d00)
Location: net/ipv4/af_inet.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv4/af_inet.c:ipip_gro_complete
  - net/ipv6/ip6_offload.c:ip4ip6_gro_complete
```
**Symbols:**

```
ffffffff81a08d00-ffffffff81a08e16: inet_gro_complete (STB_GLOBAL)
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
