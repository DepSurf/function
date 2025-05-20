# Function: <code>skb_eth_push</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f016c)
Location: net/core/skbuff.c:5670
Inline: True
```
**Symbols:**

```
ffffffff81c309e6-ffffffff81c309fe: skb_eth_push.cold (STB_LOCAL)
ffffffff819f00e0-ffffffff819f027e: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4aa6)
Location: net/core/skbuff.c:5758
Inline: True
```
**Symbols:**

```
ffffffff81c22cbb-ffffffff81c22cd3: skb_eth_push.cold (STB_LOCAL)
ffffffff819d4a20-ffffffff819d4bb6: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84836)
Location: net/core/skbuff.c:5833
Inline: True
```
**Symbols:**

```
ffffffff81d35243-ffffffff81d3525b: skb_eth_push.cold (STB_LOCAL)
ffffffff81a847b0-ffffffff81a84946: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfa852)
Location: net/core/skbuff.c:5754
Inline: True
```
**Symbols:**

```
ffffffff81f01823-ffffffff81f0183b: skb_eth_push.cold (STB_LOCAL)
ffffffff81bfa7d0-ffffffff81bfa970: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9400)
Location: net/core/skbuff.c:5956
Inline: True
```
**Symbols:**

```
ffffffff81da9400-ffffffff81da95b4: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18130)
Location: net/core/skbuff.c:6007
Inline: True
```
**Symbols:**

```
ffffffff81e18130-ffffffff81e182e4: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int skb_eth_push(struct sk_buff *skb, const unsigned char *dst, const unsigned char *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed55d0)
Location: net/core/skbuff.c:6160
Inline: True
```
**Symbols:**

```
ffffffff81ed55d0-ffffffff81ed5784: skb_eth_push (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
