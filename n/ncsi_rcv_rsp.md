# Function: <code>ncsi_rcv_rsp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff8188dcb0)
Location: net/ncsi/ncsi-rsp.c:966
Inline: False
```
**Symbols:**

```
ffffffff8188dcb0-ffffffff8188de5a: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff818c1e60)
Location: net/ncsi/ncsi-rsp.c:966
Inline: False
```
**Symbols:**

```
ffffffff818c1e60-ffffffff818c200a: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff818e87d0)
Location: net/ncsi/ncsi-rsp.c:966
Inline: False
```
**Symbols:**

```
ffffffff818e87d0-ffffffff818e8984: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff8196dc50)
Location: net/ncsi/ncsi-rsp.c:971
Inline: False
```
**Symbols:**

```
ffffffff8196dc50-ffffffff8196de55: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff819c7770)
Location: net/ncsi/ncsi-rsp.c:940
Inline: False
```
**Symbols:**

```
ffffffff819c7770-ffffffff819c796a: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff819ff180)
Location: net/ncsi/ncsi-rsp.c:1095
Inline: False
```
**Symbols:**

```
ffffffff819ff180-ffffffff819ff4b8: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1098
Inline: False
```
**Symbols:**

```
ffffffff81a6e730-ffffffff81a6e7a8: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81a6e480-ffffffff81a6e6de: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffff81aa5100-ffffffff81aa5178: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81aa4e50-ffffffff81aa50ae: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81ba0bd0-ffffffff81ba0c48: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81ba0920-ffffffff81ba0b7e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81c3382a-ffffffff81c338a2: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81bb0300-ffffffff81bb055e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81c25b4d-ffffffff81c25bc5: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81b9f400-ffffffff81b9f65e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1160
Inline: False
```
**Symbols:**

```
ffffffff81d42485-ffffffff81d4257c: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81c6cba0-ffffffff81c6cecb: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1160
Inline: False
```
**Symbols:**

```
ffffffff81f0ee12-ffffffff81f0ef06: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81e105a0-ffffffff81e108a8: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1160
Inline: False
```
**Symbols:**

```
ffffffff820b58f6-ffffffff820b5954: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81fe6cb0-ffffffff81fe704c: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1111
Inline: False
```
**Symbols:**

```
ffffffff82136e79-ffffffff82136ed7: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff82062f00-ffffffff8206329c: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1172
Inline: False
```
**Symbols:**

```
ffffffff82218cdb-ffffffff82218d39: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff82136040-ffffffff821363dc: ncsi_rcv_rsp (STB_GLOBAL)
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
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffff800010d76f08)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffff800010d76f08-ffff800010d7725c: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (c0e73664)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
c0e73664-c0e73934: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (c000000000eb6c10)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
c000000000eb6c10-c000000000eb6fa4: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffe0008a6db0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffe0008a6db0-ffffffe0008a7008: ncsi_rcv_rsp (STB_GLOBAL)
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
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffff81a44490-ffffffff81a44508: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81a441e0-ffffffff81a4443e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffff81a01080-ffffffff81a010f8: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81a00dd0-ffffffff81a0102e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffff81ab0340-ffffffff81ab03b8: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81ab0090-ffffffff81ab02ee: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_rcv_rsp(struct sk_buff *skb, struct net_device *dev, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:1105
Inline: False
```
**Symbols:**

```
ffffffff81abc6f0-ffffffff81abc768: ncsi_rcv_rsp.cold (STB_LOCAL)
ffffffff81abc440-ffffffff81abc69e: ncsi_rcv_rsp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
