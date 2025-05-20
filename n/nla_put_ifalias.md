# Function: <code>nla_put_ifalias</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185ce30)
Location: net/core/rtnetlink.c:1363
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8185ce30-ffffffff8185ced7: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1463
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818a7790-ffffffff818a782b: nla_put_ifalias (STB_LOCAL)
ffffffff818ad572-ffffffff818ad58a: nla_put_ifalias.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1515
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818cb900-ffffffff818cb99b: nla_put_ifalias (STB_LOCAL)
ffffffff818d17d2-ffffffff818d17ea: nla_put_ifalias.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81918a20-ffffffff81918ab9: nla_put_ifalias (STB_LOCAL)
ffffffff8191e735-ffffffff8191e74d: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8194b040-ffffffff8194b0d9: nla_put_ifalias (STB_LOCAL)
ffffffff81950cd0-ffffffff81950ce8: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1552
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a1be70-ffffffff81a1bf04: nla_put_ifalias (STB_LOCAL)
ffffffff81a21b68-ffffffff81a21b80: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1563
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a1c060-ffffffff81a1c0f4: nla_put_ifalias (STB_LOCAL)
ffffffff81c3168d-ffffffff81c316a5: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1565
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a02e30-ffffffff81a02ec4: nla_put_ifalias (STB_LOCAL)
ffffffff81c23996-ffffffff81c239ae: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1554
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81ab57d0-ffffffff81ab5864: nla_put_ifalias (STB_LOCAL)
ffffffff81d36dfa-ffffffff81d36e12: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1594
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81c2ea70-ffffffff81c2eb23: nla_put_ifalias (STB_LOCAL)
ffffffff81f03710-ffffffff81f03728: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de1cc0)
Location: net/core/rtnetlink.c:1605
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81de1cc0-ffffffff81de1d85: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e53c40)
Location: net/core/rtnetlink.c:1616
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81e53c40-ffffffff81e53d05: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f12fa0)
Location: net/core/rtnetlink.c:1623
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81f12fa0-ffffffff81f13065: nla_put_ifalias (STB_LOCAL)
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
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bedfb8)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffff800010bedfb8-ffff800010bee07c: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d064e0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
c0d064e0-c0d06598: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd1920)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
c000000000cd1920-c000000000cd1a0c: nla_put_ifalias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076fb72)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffe00076fb72-ffffffe00076fbdc: nla_put_ifalias (STB_LOCAL)
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
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818eb010-ffffffff818eb0a9: nla_put_ifalias (STB_LOCAL)
ffffffff818f0ca0-ffffffff818f0cb8: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818a4e50-ffffffff818a4ee9: nla_put_ifalias (STB_LOCAL)
ffffffff818aaae0-ffffffff818aaaf8: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8193c040-ffffffff8193c0d9: nla_put_ifalias (STB_LOCAL)
ffffffff81941cd0-ffffffff81941ce8: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nla_put_ifalias(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1514
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8195d8b0-ffffffff8195d949: nla_put_ifalias (STB_LOCAL)
ffffffff819635d0-ffffffff819635e8: nla_put_ifalias.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
