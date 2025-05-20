# Function: <code>ipv6_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81800c80)
Location: net/ipv6/ip6_offload.c:166
Inline: False
```
**Symbols:**

```
ffffffff81800c80-ffffffff81800f8e: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81872410)
Location: net/ipv6/ip6_offload.c:158
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81872410-ffffffff81872782: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818a6a00)
Location: net/ipv6/ip6_offload.c:161
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff818a6a00-ffffffff818a6d82: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818cd470)
Location: net/ipv6/ip6_offload.c:164
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff818cd470-ffffffff818cd7fc: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81952260)
Location: net/ipv6/ip6_offload.c:164
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81952260-ffffffff819525ee: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **ipv6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819ab7d0)
Location: net/ipv6/ip6_offload.c:167
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff819ab7d0-ffffffff819abb8a: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e22f0)
Location: net/ipv6/ip6_offload.c:188
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff819e22f0-ffffffff819e276f: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a50fb0)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81a50fb0-ffffffff81a51409: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a87bd0)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81a87bd0-ffffffff81a88029: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b83080)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81b83080-ffffffff81b834fe: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b92730)
Location: net/ipv6/ip6_offload.c:182
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81b92730-ffffffff81b92bb3: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b81880)
Location: net/ipv6/ip6_offload.c:183
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81b81880-ffffffff81b81d02: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81c4d8c0)
Location: net/ipv6/ip6_offload.c:185
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81c4d8c0-ffffffff81c4dd82: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81dedfa0)
Location: net/ipv6/ip6_offload.c:207
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81dedfa0-ffffffff81dee445: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81fc2550)
Location: net/ipv6/ip6_offload.c:188
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff81fc2550-ffffffff81fc2a34: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff820234d0)
Location: net/ipv6/ip6_offload.c:189
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff820234d0-ffffffff820239c4: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff820f25c0)
Location: net/ipv6/ip6_offload.c:220
Inline: False
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/ethernet/eth.c:eth_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
  - net/8021q/vlan_core.c:vlan_gro_receive
```
**Symbols:**

```
ffffffff820f25c0-ffffffff820f2b2d: ipv6_gro_receive (STB_GLOBAL)
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
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffff800010d54788)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffff800010d54788-ffff800010d54b80: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c0e54d64)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
c0e54d64-c0e551b8: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c000000000e8d270)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
c000000000e8d270-c000000000e8d780: ipv6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffe00088c0f6)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffe00088c0f6-ffffffe00088c4c4: ipv6_gro_receive (STB_LOCAL)
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
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a27260)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81a27260-ffffffff81a276b9: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e4020)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff819e4020-ffffffff819e4479: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a92e10)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81a92e10-ffffffff81a93269: ipv6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *ipv6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a9ef50)
Location: net/ipv6/ip6_offload.c:184
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/ipv6/ip6_offload.c:sit_ip6ip6_gro_receive
```
**Symbols:**

```
ffffffff81a9ef50-ffffffff81a9f3b9: ipv6_gro_receive (STB_GLOBAL)
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
