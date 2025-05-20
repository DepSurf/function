# Function: <code>__skb_flow_dissect_arp</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c4f9e)
Location: net/core/flow_dissector.c:170
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183ea4f)
Location: net/core/flow_dissector.c:263
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81889653)
Location: net/core/flow_dissector.c:265
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818aa203)
Location: net/core/flow_dissector.c:335
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f5409)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819272e7)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819faf80)
Location: net/core/flow_dissector.c:445
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819faf80-ffffffff819fb0f2: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819faba0)
Location: net/core/flow_dissector.c:462
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819faba0-ffffffff819facf6: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e0da0)
Location: net/core/flow_dissector.c:468
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819e0da0-ffffffff819e0f08: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a911e0)
Location: net/core/flow_dissector.c:469
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81a911e0-ffffffff81a91348: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c072a0)
Location: net/core/flow_dissector.c:471
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81c072a0-ffffffff81c07448: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db6d00)
Location: net/core/flow_dissector.c:495
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81db6d00-ffffffff81db6ea8: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e273c0)
Location: net/core/flow_dissector.c:505
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81e273c0-ffffffff81e27568: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_arp(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, const void *data, int nhoff, int hlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee5710)
Location: net/core/flow_dissector.c:549
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81ee5710-ffffffff81ee58b9: __skb_flow_dissect_arp (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc3850)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (c0cdeb8c)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9da10)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffe0007502da)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c72e7)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81881227)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819182e7)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8193968d)
Location: net/core/flow_dissector.c:435
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
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
