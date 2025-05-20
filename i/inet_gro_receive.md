# Function: <code>inet_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81793ba0)
Location: net/ipv4/af_inet.c:1289
Inline: False
```
**Symbols:**

```
ffffffff81793ba0-ffffffff81793da0: inet_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818012d0)
Location: net/ipv4/af_inet.c:1285
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff818012d0-ffffffff81801569: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818320e0)
Location: net/ipv4/af_inet.c:1297
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff818320e0-ffffffff81832379: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81854b70)
Location: net/ipv4/af_inet.c:1315
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81854b70-ffffffff81854e25: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d4a10)
Location: net/ipv4/af_inet.c:1319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff818d4a10-ffffffff818d4cc7: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **inet_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192af50)
Location: net/ipv4/af_inet.c:1388
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff8192af50-ffffffff8192b200: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81958bd0)
Location: net/ipv4/af_inet.c:1392
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81958bd0-ffffffff81958e95: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bd6a0)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff819bd6a0-ffffffff819bd969: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f42b0)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff819f42b0-ffffffff819f4579: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae2b70)
Location: net/ipv4/af_inet.c:1439
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81ae2b70-ffffffff81ae2e50: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aefa30)
Location: net/ipv4/af_inet.c:1433
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81aefa30-ffffffff81aefd33: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adb180)
Location: net/ipv4/af_inet.c:1436
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81adb180-ffffffff81adb47c: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9a530)
Location: net/ipv4/af_inet.c:1441
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81b9a530-ffffffff81b9a82c: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2c8d0)
Location: net/ipv4/af_inet.c:1436
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81d2c8d0-ffffffff81d2cba0: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef4190)
Location: net/ipv4/af_inet.c:1456
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81ef4190-ffffffff81ef4466: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f53a80)
Location: net/ipv4/af_inet.c:1455
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81f53a80-ffffffff81f53d5d: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff82019e40)
Location: net/ipv4/af_inet.c:1475
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff82019e40-ffffffff8201a11d: inet_gro_receive (STB_GLOBAL)
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
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010caa210)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffff800010caa210-ffff800010caa500: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db69a8)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
c0db69a8-c0db6cb8: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc0240)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
c000000000dc0240-c000000000dc05ec: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe00080504c)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffe00080504c-ffffffe000805322: inet_gro_receive (STB_GLOBAL)
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
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81994050)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81994050-ffffffff81994319: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194db10)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff8194db10-ffffffff8194ddd9: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fe8f0)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff819fe8f0-ffffffff819febb9: inet_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *inet_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a0a680)
Location: net/ipv4/af_inet.c:1407
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv4/af_inet.c:ipip_gro_receive
  - net/ipv6/ip6_offload.c:ip4ip6_gro_receive
```
**Symbols:**

```
ffffffff81a0a680-ffffffff81a0a988: inet_gro_receive (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
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
