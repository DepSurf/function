# Function: <code>ipv6_gro_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81800a90)
Location: net/ipv6/ip6_offload.c:261
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81800a90-ffffffff81800b3b: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81872210)
Location: net/ipv6/ip6_offload.c:287
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81872210-ffffffff818722ba: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818a67f0)
Location: net/ipv6/ip6_offload.c:291
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff818a67f0-ffffffff818a68af: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818cd250)
Location: net/ipv6/ip6_offload.c:294
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff818cd250-ffffffff818cd2fd: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81952030)
Location: net/ipv6/ip6_offload.c:294
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81952030-ffffffff819520e1: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819ab5b0)
Location: net/ipv6/ip6_offload.c:297
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff819ab5b0-ffffffff819ab661: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e2070)
Location: net/ipv6/ip6_offload.c:328
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff819e2070-ffffffff819e213c: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_offload.c (0)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81a517ec-ffffffff81a51804: ipv6_gro_complete.cold (STB_LOCAL)
ffffffff81a50d00-ffffffff81a50dcd: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a87920)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81a87920-ffffffff81a879eb: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b82de0)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81b82de0-ffffffff81b82eae: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b92460)
Location: net/ipv6/ip6_offload.c:320
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81b92460-ffffffff81b92553: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b815b0)
Location: net/ipv6/ip6_offload.c:321
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81b815b0-ffffffff81b816a3: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81c4d5d0)
Location: net/ipv6/ip6_offload.c:323
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81c4d5d0-ffffffff81c4d6c3: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81dedb80)
Location: net/ipv6/ip6_offload.c:342
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81dedb80-ffffffff81dedd22: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81fc1aa0)
Location: net/ipv6/ip6_offload.c:320
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff81fc1aa0-ffffffff81fc1c42: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff82022a20)
Location: net/ipv6/ip6_offload.c:321
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff82022a20-ffffffff82022bc2: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff820f1b40)
Location: net/ipv6/ip6_offload.c:349
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
  - net/8021q/vlan_core.c:vlan_gro_complete
```
**Symbols:**

```
ffffffff820f1b40-ffffffff820f1ce9: ipv6_gro_complete (STB_GLOBAL)
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
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffff800010d54500)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffff800010d54500-ffff800010d545e4: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c0e54af8)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
c0e54af8-c0e54be8: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c000000000e8cef0)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
c000000000e8cef0-c000000000e8d004: ipv6_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffe00088beb0)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffe00088beb0-ffffffe00088bf82: ipv6_gro_complete (STB_LOCAL)
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
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a26fb0)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81a26fb0-ffffffff81a2707b: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e3d70)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff819e3d70-ffffffff819e3e3b: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a92b60)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81a92b60-ffffffff81a92c2b: ipv6_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a9ec60)
Location: net/ipv6/ip6_offload.c:324
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_complete
  - net/ipv6/ip6_offload.c:ip6ip6_gro_complete
  - net/ipv6/ip6_offload.c:sit_gro_complete
```
**Symbols:**

```
ffffffff81a9ec60-ffffffff81a9ed68: ipv6_gro_complete (STB_GLOBAL)
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
