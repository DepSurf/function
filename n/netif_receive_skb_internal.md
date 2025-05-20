# Function: <code>netif_receive_skb_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ab70)
Location: net/core/dev.c:3988
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff8171ab70-ffffffff8171ac0b: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783080)
Location: net/core/dev.c:4260
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81783080-ffffffff8178311b: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b0920)
Location: net/core/dev.c:4260
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff817b0920-ffffffff817b09bb: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0990)
Location: net/core/dev.c:4459
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff817d0990-ffffffff817d0d73: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184ada0)
Location: net/core/dev.c:4602
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff8184ada0-ffffffff8184ae68: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81895180)
Location: net/core/dev.c:4732
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81895180-ffffffff81895268: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5c50)
Location: net/core/dev.c:5151
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff818b5c50-ffffffff818b5d38: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81902b20)
Location: net/core/dev.c:5190
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_complete
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81902b20-ffffffff81902bd1: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81934d60)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81934d60-ffffffff81934e11: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09a00)
Location: net/core/dev.c:5475
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81a09a00-ffffffff81a09aaf: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0afa0)
Location: net/core/dev.c:5532
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81a0afa0-ffffffff81a0b065: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f3588)
Location: net/core/dev.c:5656
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa4ee5)
Location: net/core/dev.c:5626
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1b7e7)
Location: net/core/dev.c:5663
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcc797)
Location: net/core/dev.c:5654
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3d2f7)
Location: net/core/dev.c:5630
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efbb97)
Location: net/core/dev.c:5712
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd2f68)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffff800010bd2f68-ffff800010bd3034: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cedc88)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
c0cedc88-c0cedd84: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb1950)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
c000000000cb1950-c000000000cb1a54: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075d32c)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffe00075d32c-ffffffe00075d3ca: netif_receive_skb_internal (STB_LOCAL)
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
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d4d60)
Location: net/core/dev.c:5092
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff818d4d60-ffffffff818d4dff: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ebf0)
Location: net/core/dev.c:5092
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff8188ebf0-ffffffff8188ec8f: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81925d60)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff81925d60-ffffffff81925e11: netif_receive_skb_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netif_receive_skb_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819472a0)
Location: net/core/dev.c:5092
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
```
**Symbols:**

```
ffffffff819472a0-ffffffff81947373: netif_receive_skb_internal (STB_LOCAL)
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
