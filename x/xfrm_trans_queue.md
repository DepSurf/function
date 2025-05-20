# Function: <code>xfrm_trans_queue</code>

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
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818fee90)
Location: net/xfrm/xfrm_input.c:509
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff818fee90-ffffffff818feefb: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81955950)
Location: net/xfrm/xfrm_input.c:515
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81955950-ffffffff819559b9: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8198a430)
Location: net/xfrm/xfrm_input.c:497
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8198a430-ffffffff8198a499: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f4780)
Location: net/xfrm/xfrm_input.c:769
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff819f4780-ffffffff819f47f0: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a2b430)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81a2b430-ffffffff81a2b4a0: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1d8f0)
Location: net/xfrm/xfrm_input.c:796
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81b1d8f0-ffffffff81b1d973: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2c1c0)
Location: net/xfrm/xfrm_input.c:798
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81b2c1c0-ffffffff81b2c243: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b19e20)
Location: net/xfrm/xfrm_input.c:798
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81b19e20-ffffffff81b19ea3: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde440)
Location: net/xfrm/xfrm_input.c:798
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81bde440-ffffffff81bde4c8: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d75260)
Location: net/xfrm/xfrm_input.c:798
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81d75260-ffffffff81d752f7: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41820)
Location: net/xfrm/xfrm_input.c:808
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81f41820-ffffffff81f4184e: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa10c0)
Location: net/xfrm/xfrm_input.c:784
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff81fa10c0-ffffffff81fa10ee: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e3e0)
Location: net/xfrm/xfrm_input.c:782
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
**Symbols:**

```
ffffffff8206e3e0-ffffffff8206e40e: xfrm_trans_queue (STB_GLOBAL)
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
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffff800010ce9fa8)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffff800010ce9fa8-ffff800010cea090: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c0df1e5c)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
c0df1e5c-c0df1efc: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c000000000e0d810)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
c000000000e0d810-c000000000e0d8f8: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffe000837b8a)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffe000837b8a-ffffffe000837c22: xfrm_trans_queue (STB_GLOBAL)
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
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819caac0)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff819caac0-ffffffff819cab30: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819878b0)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff819878b0-ffffffff81987920: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a35540)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81a35540-ffffffff81a355b0: xfrm_trans_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_trans_queue(struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a40ea0)
Location: net/xfrm/xfrm_input.c:772
Inline: False
Direct callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81a40ea0-ffffffff81a40f10: xfrm_trans_queue (STB_GLOBAL)
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
