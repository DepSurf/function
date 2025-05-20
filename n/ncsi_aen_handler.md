# Function: <code>ncsi_aen_handler</code>

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
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff8188e190)
Location: net/ncsi/ncsi-aen.c:164
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff8188e190-ffffffff8188e283: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff818c2430)
Location: net/ncsi/ncsi-aen.c:193
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff818c2430-ffffffff818c2523: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff818e8dc0)
Location: net/ncsi/ncsi-aen.c:193
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff818e8dc0-ffffffff818e8eb3: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff8196e300)
Location: net/ncsi/ncsi-aen.c:198
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff8196e300-ffffffff8196e42f: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff819c7d50)
Location: net/ncsi/ncsi-aen.c:169
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff819c7d50-ffffffff819c7e7f: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff819ff9b0)
Location: net/ncsi/ncsi-aen.c:212
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff819ff9b0-ffffffff819ffadf: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81a6ed98-ffffffff81a6edd1: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81a6ec80-ffffffff81a6ed7b: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81aa5768-ffffffff81aa57a1: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81aa5650-ffffffff81aa574b: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81ba1235-ffffffff81ba126b: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81ba1120-ffffffff81ba1218: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81c338bf-ffffffff81c338f5: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81bb0a30-ffffffff81bb0b28: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81c25be2-ffffffff81c25c18: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81b9fb30-ffffffff81b9fc28: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81d425c3-ffffffff81d425f9: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81c6d3b0-ffffffff81c6d4a8: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81f0ef4d-ffffffff81f0ef83: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81e10de0-ffffffff81e10eeb: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff81fe75e0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81fe75e0-ffffffff81fe7741: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff82063840)
Location: net/ncsi/ncsi-aen.c:209
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff82063840-ffffffff820639a1: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffff82136980)
Location: net/ncsi/ncsi-aen.c:209
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff82136980-ffffffff82136ae1: ncsi_aen_handler (STB_GLOBAL)
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
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffff800010d77b80)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffff800010d77b80-ffff800010d77cf0: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (c0e73e5c)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
c0e73e5c-c0e73fa4: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (c000000000eb75c0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
c000000000eb75c0-c000000000eb77b0: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-aen.c (ffffffe0008a74a0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffe0008a74a0-ffffffe0008a761e: ncsi_aen_handler (STB_GLOBAL)
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
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81a44af8-ffffffff81a44b31: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81a449e0-ffffffff81a44adb: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81a016e8-ffffffff81a01721: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81a015d0-ffffffff81a016cb: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81ab09a8-ffffffff81ab09e1: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81ab0890-ffffffff81ab098b: ncsi_aen_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_aen_handler(struct ncsi_dev_priv *ndp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-aen.c (0)
Location: net/ncsi/ncsi-aen.c:208
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
```
**Symbols:**

```
ffffffff81abcd58-ffffffff81abcd91: ncsi_aen_handler.cold (STB_LOCAL)
ffffffff81abcc40-ffffffff81abcd3b: ncsi_aen_handler (STB_GLOBAL)
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
