# Function: <code>rtnetlink_ifinfo_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81809b70)
Location: net/wireless/wext-core.c:417
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81809b70-ffffffff81809c64: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8187b670)
Location: net/wireless/wext-core.c:420
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8187b670-ffffffff8187b764: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818aff30)
Location: net/wireless/wext-core.c:420
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818aff30-ffffffff818b0024: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818d6910)
Location: net/wireless/wext-core.c:420
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818d6910-ffffffff818d69ec: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8195c4e0)
Location: net/wireless/wext-core.c:420
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8195c4e0-ffffffff8195c5bc: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819b5d00)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819b5d00-ffffffff819b5dda: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819ecfc0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819ecfc0-ffffffff819ed097: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81a5c1a0-ffffffff81a5c289: rtnetlink_ifinfo_prep (STB_LOCAL)
ffffffff81a5ce1e-ffffffff81a5ce38: rtnetlink_ifinfo_prep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a92dd0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81a92dd0-ffffffff81a92eb3: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81b8e0e0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81b8e0e0-ffffffff81b8e1c5: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81b9dd70-ffffffff81b9de6e: rtnetlink_ifinfo_prep (STB_LOCAL)
ffffffff81c332e4-ffffffff81c332fc: rtnetlink_ifinfo_prep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81b8ce70-ffffffff81b8cf6d: rtnetlink_ifinfo_prep (STB_LOCAL)
ffffffff81c25603-ffffffff81c2561b: rtnetlink_ifinfo_prep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81c59210-ffffffff81c5930d: rtnetlink_ifinfo_prep (STB_LOCAL)
ffffffff81d41b44-ffffffff81d41b5c: rtnetlink_ifinfo_prep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81dfa970-ffffffff81dfaa6f: rtnetlink_ifinfo_prep (STB_LOCAL)
ffffffff81f0e470-ffffffff81f0e488: rtnetlink_ifinfo_prep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81fcf120)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81fcf120-ffffffff81fcf22f: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8204ad50)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8204ad50-ffffffff8204ae5a: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8211d1d0)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8211d1d0-ffffffff8211d2de: rtnetlink_ifinfo_prep (STB_LOCAL)
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
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffff800010d60bd8)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffff800010d60bd8-ffff800010d60ccc: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c0e60420)
Location: net/wireless/wext-core.c:418
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c000000000e9bf20)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
c000000000e9bf20-c000000000e9c08c: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffe000895e58)
Location: net/wireless/wext-core.c:418
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
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
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a32460)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81a32460-ffffffff81a32543: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819ef650)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819ef650-ffffffff819ef733: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a9e010)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81a9e010-ffffffff81a9e0f3: rtnetlink_ifinfo_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nlmsghdr *rtnetlink_ifinfo_prep(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81aaa210)
Location: net/wireless/wext-core.c:418
Inline: False
Direct callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81aaa210-ffffffff81aaa2f3: rtnetlink_ifinfo_prep (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
