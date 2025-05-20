# Function: <code>netlink_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174b010)
Location: net/netlink/af_netlink.c:1796
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8174b010-ffffffff8174b0dd: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b73d0)
Location: net/netlink/af_netlink.c:1179
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff817b73d0-ffffffff817b74a9: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e6e70)
Location: net/netlink/af_netlink.c:1196
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff817e6e70-ffffffff817e6f49: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81806bc0)
Location: net/netlink/af_netlink.c:1230
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81806bc0-ffffffff81806c89: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818858a0)
Location: net/netlink/af_netlink.c:1243
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff818858a0-ffffffff81885969: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d9240)
Location: net/netlink/af_netlink.c:1282
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff818d9240-ffffffff818d9308: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81905a30)
Location: net/netlink/af_netlink.c:1275
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81905a30-ffffffff81905af8: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:1267
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81966c80-ffffffff81966d49: netlink_trim (STB_LOCAL)
ffffffff8196b097-ffffffff8196b0aa: netlink_trim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d700)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8199d700-ffffffff8199d7d0: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76710)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a76710-ffffffff81a767ce: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7f460)
Location: net/netlink/af_netlink.c:1269
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a7f460-ffffffff81a7f51e: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a68440)
Location: net/netlink/af_netlink.c:1279
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a68440-ffffffff81a684fe: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b219b0)
Location: net/netlink/af_netlink.c:1284
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81b219b0-ffffffff81b21a6e: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caa150)
Location: net/netlink/af_netlink.c:1284
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81caa150-ffffffff81caa222: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e67220)
Location: net/netlink/af_netlink.c:1304
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81e67220-ffffffff81e672f2: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec2fd0)
Location: net/netlink/af_netlink.c:1304
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81ec2fd0-ffffffff81ec30a2: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f86320)
Location: net/netlink/af_netlink.c:1306
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81f86320-ffffffff81f863f2: netlink_trim (STB_LOCAL)
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
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4aba0)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffff800010c4aba0-ffff800010c4ac84: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5b780)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
c0d5b780-c0d5b870: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48c70)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
c000000000d48c70-c000000000d48dc8: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b7f36)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffe0007b7f36-ffffffe0007b7fe6: netlink_trim (STB_LOCAL)
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
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d570)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8193d570-ffffffff8193d640: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f7070)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff818f7070-ffffffff818f7140: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e700)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8198e700-ffffffff8198e7d0: netlink_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *netlink_trim(struct sk_buff *skb, gfp_t allocation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b0fb0)
Location: net/netlink/af_netlink.c:1268
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff819b0fb0-ffffffff819b1080: netlink_trim (STB_LOCAL)
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
