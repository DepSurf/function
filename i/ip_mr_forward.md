# Function: <code>ip_mr_forward</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct sk_buff *skb, struct mfc_cache *cache, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a9870)
Location: net/ipv4/ipmr.c:1806
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff817a9870-ffffffff817a9b45: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct sk_buff *skb, struct mfc_cache *cache, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818170a0)
Location: net/ipv4/ipmr.c:1785
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818170a0-ffffffff818173b4: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct sk_buff *skb, struct mfc_cache *cache, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818488c0)
Location: net/ipv4/ipmr.c:1790
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818488c0-ffffffff81848c21: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *cache, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186b8d0)
Location: net/ipv4/ipmr.c:1838
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
**Symbols:**

```
ffffffff8186b8d0-ffffffff8186bbf0: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *cache, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ec120)
Location: net/ipv4/ipmr.c:1999
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818ec120-ffffffff818ec46d: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81940d80)
Location: net/ipv4/ipmr.c:1928
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81940d80-ffffffff819410cd: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81970d70)
Location: net/ipv4/ipmr.c:1938
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81970d70-ffffffff819710da: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819da520)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819da520-ffffffff819da855: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a113a0)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a113a0-ffffffff81a116d5: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b02a50)
Location: net/ipv4/ipmr.c:1918
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff81b02a50-ffffffff81b02d85: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b10e30)
Location: net/ipv4/ipmr.c:1925
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff81b10e30-ffffffff81b11165: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afebc0)
Location: net/ipv4/ipmr.c:1925
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81afebc0-ffffffff81afeef5: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1927
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81bc0490-ffffffff81bc0ace: ip_mr_forward (STB_LOCAL)
ffffffff81d3ea4a-ffffffff81d3eab6: ip_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1921
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff81d54d30-ffffffff81d55397: ip_mr_forward (STB_LOCAL)
ffffffff81f0b361-ffffffff81f0b3d0: ip_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1940
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff81f1eff0-ffffffff81f1f696: ip_mr_forward (STB_LOCAL)
ffffffff820b2c2c-ffffffff820b2c80: ip_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1955
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff81f7eaf0-ffffffff81f7f199: ip_mr_forward (STB_LOCAL)
ffffffff82133de4-ffffffff82133e38: ip_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1953
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
**Symbols:**

```
ffffffff82045170-ffffffff82045819: ip_mr_forward (STB_LOCAL)
ffffffff822157f0-ffffffff82215844: ip_mr_forward.cold (STB_LOCAL)
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
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccd008)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffff800010ccd008-ffff800010ccd35c: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd781c)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c0dd781c-c0dd7b68: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de8d70)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c000000000de8d70-c000000000de9200: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081f034)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffe00081f034-ffffffe00081f308: ip_mr_forward (STB_LOCAL)
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
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b0d30)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819b0d30-ffffffff819b1065: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196d360)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8196d360-ffffffff8196d695: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1b5d0)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a1b5d0-ffffffff81a1b905: ip_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc_cache *c, int local);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a264b0)
Location: net/ipv4/ipmr.c:1950
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a264b0-ffffffff81a267e5: ip_mr_forward (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, mrt, skb, cache, local</code> ➡️ <code>net, mrt, dev, skb, cache, local</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mfc_cache *c</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mfc_cache *cache</code>
</li>
</ul>
</details>
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
