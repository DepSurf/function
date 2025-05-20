# Function: <code>skb_gso_transport_seglen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705340)
Location: net/core/skbuff.c:4316
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81705340-ffffffff817053bb: skb_gso_transport_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176bf10)
Location: net/core/skbuff.c:4356
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
```
**Symbols:**

```
ffffffff8176bf10-ffffffff8176bf91: skb_gso_transport_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817990f0)
Location: net/core/skbuff.c:4400
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
```
**Symbols:**

```
ffffffff817990f0-ffffffff81799171: skb_gso_transport_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b76c0)
Location: net/core/skbuff.c:4494
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff817b76c0-ffffffff817b774e: skb_gso_transport_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fd80)
Location: net/core/skbuff.c:4888
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_mtu
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff8182fd80-ffffffff8182fe0e: skb_gso_transport_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a400)
Location: net/core/skbuff.c:4927
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff8187a400-ffffffff8187a49a: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b010)
Location: net/core/skbuff.c:4953
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff8189b010-ffffffff8189b0aa: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e56f0)
Location: net/core/skbuff.c:5138
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff818e56f0-ffffffff818e578a: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917840)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81917840-ffffffff819178da: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9e80)
Location: net/core/skbuff.c:5252
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff819e9e80-ffffffff819e9f1a: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9c20)
Location: net/core/skbuff.c:5319
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff819e9c20-ffffffff819e9cba: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cfd60)
Location: net/core/skbuff.c:5407
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff819cfd60-ffffffff819cfdf5: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f790)
Location: net/core/skbuff.c:5482
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81a7f790-ffffffff81a7f825: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3bd0)
Location: net/core/skbuff.c:5403
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81bf3bd0-ffffffff81bf3c83: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1930)
Location: net/core/skbuff.c:5605
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81da1930-ffffffff81da19e3: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81e7d3f0)
Location: net/core/gso.c:143
Inline: False
Direct callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81e7d3f0-ffffffff81e7d4a3: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81f3e370)
Location: net/core/gso.c:143
Inline: False
Direct callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81f3e370-ffffffff81f3e423: skb_gso_transport_seglen (STB_LOCAL)
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
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0bd0)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffff800010bb0bd0-ffff800010bb0c88: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdf68)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
c0ccdf68-c0cce004: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86de0)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
c000000000c86de0-c000000000c86ea4: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741d9a)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffe000741d9a-ffffffe000741e2e: skb_gso_transport_seglen (STB_LOCAL)
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
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7840)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff818b7840-ffffffff818b78da: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871790)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81871790-ffffffff8187182a: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908840)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff81908840-ffffffff819088da: skb_gso_transport_seglen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int skb_gso_transport_seglen(const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819298f0)
Location: net/core/skbuff.c:5150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
```
**Symbols:**

```
ffffffff819298f0-ffffffff8192998a: skb_gso_transport_seglen (STB_LOCAL)
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
